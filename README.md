# EECS839-Final-Project

# Implementation of MLEM2 Algorithm 


Guojun Xiong
KUID: 2946078


# Description of the project

In this project, we simulate the MLEM2 algorithm by using concept approximation. It contains three '.py' files under the name of 'MLEM2_Algorithm.py', 'Data_process.py', 'Concept_approx.py'. 


# Intro for each '.py' file
'Data_process.py' contains several essential functions to process the data read from the input files, which transfer the data in the original input file into python data structure. 

'Concept_apporx.py' is the file containing the MLEM2 algorithm. 

'MLEM2_Algorithm.py' is the main file of this project. 

# Run 'MLEM2_Algorithm.py' 
When run 'MLEM2_Algorithm.py', it first asks to enter the name of input file. 
Second, it asks to indicate what type of concept approximation will be adopted. 
Third, it asks to enter the name of output file. 

Finally, the induced rules will be saved in the output file in the way as follows: 
2, 2, 2
(Ink-color, blue) & (Body-color, blue) -> (Attitude, plus) 1, 1, 1
(Ink-color, red) -> (Attitude, plus)
1, 3, 3
(Body-color, black) -> (Attitude, minus)
1, 3, 3
(Ink-color, black) -> (Attitude, minus)
