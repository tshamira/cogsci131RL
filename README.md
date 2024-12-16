# cogsci131RL
This project was completed for the course Cognitive Science 131: Computational Models of the Mind, taught at UC Berkeley in Fall 2022 by Professor Ramirez-Latorre.
The task was to implement rules for a two-dimensional "Pac-Man" game where an agent (the 2-D "Pac-man" player) had the choice to move up, down, left, or right within a grid consisting of seven squares. The squares were arranged so that five squares were along a vertical line, and the remaining two squares were to the left and right of the middle square.
Each square on the grid was assigned a "state" and a "reward." The "state" of the grid is essentially an ID for each square, a simple number from 0 to 11 - this was used to represent the placement of our agent. The "reward" was a number ranging from -1.0 to +1.0, representing the amount of points that our agent would receive after traveling through that square. 

I used this Medium article to learn more about Markov decision processes: https://medium.com/@ngao7/markov-decision-process-basics-3da5144d3348
