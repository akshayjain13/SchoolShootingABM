# Can School Design Save Lives:
## An Agent-Based Model Evaluating the Effects of Architecture on School Shootings 

Akshay Jain's Northwestern MMSS Senior Thesis and current working paper

### What is this?

This is the code and data for my senior thesis which constructed Agent-Based Models (ABMs) in AnyLogic software (anylogic.com). This is the backing for a working paper submitted to the Journal of Computational Social Science for review. 

### What is each file/folder?

* *AnyLogic Simulations* contains the AnyLogic project folders. The .alp files are the actual AnyLogic files.
* *datasets* contains the generated csv corresponding to the AnyLogic file with the same name.
* Averages.csv is the average casualty count for each floor plan
* dataExploration.csv is the code that performs the regressions and makes graphs used in the paper
* models.htm is the regression output

### What do the file names represent?
Each 5 character alphanumeric code represents the components of the floor plan. 

* The first character (either 'C' or 'S') represents whether the floor plan has curved hallways or straight hallways, respectively.
* The second character represents the number of exits (either 1,2,3, or 4)
* The third character represents the width of the exits in meters (either 1,2, or 3)
* The fourth character represents whether there are obtacles in the floor-plan. (Y = Yes, N = No)
* The fifth character represents the width of the hallways in meters (either 2, 4, or 6)


### Video of simulation on one floor plan

https://user-images.githubusercontent.com/49322330/160303126-c468ebde-8089-4c87-95b3-e2a92304bfea.mp4

