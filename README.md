# MazeGame
pygame-based experiment script for a maze navigation task

# Requirements
- [python3](https://www.python.org/downloads/) - tested with python3
- [pygame](https://www.pygame.org/wiki/GettingStarted)
- [PsychoPy](https://www.psychopy.org/download.html) - tested with v2 & v3. Standalone version works
- Note: The codes have been tested on both Mac and PC

# Directory set-up
Put the whole MazeGame folder in your experiment directory (the directory where you keep experiment codes and run the codes from). 

# How to run the code
- in terminal,
- type *cd {path to your MazeGame directory}*
- type *python3 Maze_main_PlayMe2.py* or Maze_practice_PlayMe1.py to run a practice
- Note: Task instruction material is available upon request.

# Taking breaks in between blocks

If you need to take a break in between blocks, you can pause on the screen after a block finished which says “Navigate to find the goal object. Press a key to go proceed”.

You mustn’t close the window or terminate the Python program. However, you can swipe out of the window to minimize it, if you would like. On Mac, this is achieved by pressing the Mission Control key (or swiping up with three fingers on the trackpad). On Windows, this is achieved by pressing the Windows key.

When you are ready to return to the task, open the Pygame window and proceed to the next block.


# Data saving
- Three data files are generated and saved.
1. MazeGame/config/{subject id}_maze_seq.csv - contains the order in which mazes were presented (randomized across subjects & blocks)
	- This will be saved after the completion of the task
2. MazeGame/config/{subject id}_maze_themes.csv - contains the mapping between mazes and themes  
	- This will be saved after the completion of the task
3. MazeGame/data/{subject id}_maze_log.txt - this is the main data file
	- This will be saved after every block

## Contributors: 
- Maya Geva-Sagiv (github.com/mgevasagiv)
- Serigne Diaw (https://github.com/serignediaw9)
- April Luo (github.com/aprilluo0421)
- Kamin Kim (github.com/kaminkim)
