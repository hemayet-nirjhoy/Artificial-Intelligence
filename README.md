# Map-coloring-using-Hillclimbing-in-java
The following map is using for this problem
![Sample Map](Map.JPG)

<h1 align="center">Solutions of the Algorithms</h1>

#Hill Climbing 
![Hill-Climbing](screenshots/hill_climbing.png)

#Simulate Annealing 

*************Simulated Annealing Algorithm to solve Map coloring*************
__________________________________________________________________________
........................................
Number of iteration: 1
Temperature: 1000		 Current cost: 3
........................................
Number of iteration: 2
Temperature: 999		 Current cost: 3
........................................
Number of iteration: 3
Temperature: 998		 Current cost: 3
........................................
Number of iteration: 4
Temperature: 997		 Current cost: 4
........................................
Number of iteration: 5
Temperature: 996		 Current cost: 4
........................................
Number of iteration: 6
Temperature: 995		 Current cost: 4
........................................
Number of iteration: 7
Temperature: 994		 Current cost: 4
........................................
Number of iteration: 8
Temperature: 993		 Current cost: 4
........................................
Number of iteration: 9
Temperature: 992		 Current cost: 4
........................................
Number of iteration: 10
Temperature: 991		 Current cost: 3
........................................
Number of iteration: 11
Temperature: 990		 Current cost: 3
........................................
Number of iteration: 12
Temperature: 989		 Current cost: 4
........................................
Number of iteration: 13
Temperature: 988		 Current cost: 6
........................................
Number of iteration: 14
Temperature: 987		 Current cost: 6
........................................
Number of iteration: 15
Temperature: 986		 Current cost: 5
........................................
Number of iteration: 16
Temperature: 985		 Current cost: 3
........................................
Number of iteration: 17
Temperature: 984		 Current cost: 3
........................................
Number of iteration: 18
Temperature: 983		 Current cost: 3
........................................
Number of iteration: 19
Temperature: 982		 Current cost: 3
........................................
Number of iteration: 20
Temperature: 981		 Current cost: 2
........................................
Number of iteration: 21
Temperature: 980		 Current cost: 3
........................................
Number of iteration: 22
Temperature: 979		 Current cost: 3
........................................
Number of iteration: 23
Temperature: 978		 Current cost: 2
........................................
Number of iteration: 24
Temperature: 977		 Current cost: 1
........................................
Number of iteration: 25
Temperature: 976		 Current cost: 0
__________________________________________________________________________
Goal is found: 
Western Australia 		: RED
Northern Trritory 		: GREEN
South Australia 		: BLUE
Queens Land 			: RED
New South Wales 		: GREEN
Victoria 			: RED
Tasmia 				: RED
__________________________________________________________________________

#Genetic Algorithm

******************Generation: 1*****************
Crossover position: 5
X	: 2220102
Y	: 2000202
child	: 2220102

Muted on position: 0
Child: 0220102

Muted on position: 3
Child: 0221102

Crossover position: 4
X	: 2220102
Y	: 1110202
child	: 2220202

Muted on position: 1
Child: 2020202

Crossover position: 1
X	: 0020202
Y	: 2000202
child	: 0000202

Muted on position: 4
Child: 0000002

Crossover position: 5
X	: 0020202
Y	: 1110202
child	: 0020202

Muted on position: 3
Child: 0022202

******************Generation: 2*****************
Crossover position: 5
X	: 2020202
Y	: 0022202
child	: 2020202

Crossover position: 2
X	: 0221102
Y	: 2020202
child	: 0220202

Muted on position: 0
Child: 2220202

Muted on position: 5
Child: 2220212

Crossover position: 3
X	: 2020202
Y	: 0022202
child	: 2022202

Crossover position: 2
X	: 0022202
Y	: 0221102
child	: 0021102

******************Generation: 3*****************
Crossover position: 3
X	: 0021102
Y	: 2022202
child	: 0022202

Muted on position: 3
Child: 0020202

Crossover position: 5
X	: 2020202
Y	: 2022202
child	: 2020202

Crossover position: 1
X	: 0021102
Y	: 2220212
child	: 0220212

Muted on position: 2
Child: 0200212

Crossover position: 6
X	: 2220212
Y	: 2020202
child	: 2220212

Muted on position: 0
Child: 1220212

Muted on position: 2
Child: 1200212

Muted on position: 6
Child: 1200211

******************Generation: 4*****************
Crossover position: 1
X	: 2020202
Y	: 0020202
child	: 2020202

Muted on position: 1
Child: 2120202

Muted on position: 4
Child: 2120002

Crossover position: 4
X	: 1200211
Y	: 2020202
child	: 1200202

Muted on position: 5
Child: 1200212

Crossover position: 6
X	: 0200212
Y	: 1200211
child	: 0200211

Muted on position: 0
Child: 2200211

Muted on position: 3
Child: 2202211

Muted on position: 4
Child: 2202011

Crossover position: 3
X	: 1200211
Y	: 0020202
child	: 1200202

Muted on position: 0
Child: 0200202

Muted on position: 2
Child: 0220202

******************Generation: 5*****************
Crossover position: 4
X	: 1200212
Y	: 2120002
child	: 1200002

Muted on position: 4
Child: 1200102

Crossover position: 6
X	: 2202011
Y	: 2120002
child	: 2202012

Muted on position: 0
Child: 0202012

Muted on position: 2
Child: 0222012

Muted on position: 5
Child: 0222002

Crossover position: 4
X	: 0220202
Y	: 2202011
child	: 0220011

Muted on position: 1
Child: 0020011

Muted on position: 5
Child: 0020001

Muted on position: 6
Child: 0020000

Crossover position: 3
X	: 2120002
Y	: 1200212
child	: 2120212

Muted on position: 3
Child: 2121212

******************Generation: 6*****************
Crossover position: 5
X	: 2121212
Y	: 1200102
child	: 2121202

Muted on position: 3
Child: 2120202

Crossover position: 3
X	: 1200102
Y	: 2121212
child	: 1201212

Muted on position: 0
Child: 2201212

Crossover position: 3
X	: 2121212
Y	: 0222002
child	: 2122002

Muted on position: 1
Child: 2022002

Crossover position: 5
X	: 0020000
Y	: 0222002
child	: 0020002

Muted on position: 0
Child: 2020002

Muted on position: 3
Child: 2021002

******************Generation: 7*****************
Crossover position: 3
X	: 2021002
Y	: 2022002
child	: 2022002

Muted on position: 2
Child: 2012002

Muted on position: 5
Child: 2012022

Crossover position: 2
X	: 2201212
Y	: 2120202
child	: 2220202

Muted on position: 2
Child: 2200202

Muted on position: 4
Child: 2200002

Crossover position: 5
X	: 2201212
Y	: 2120202
child	: 2201202

Muted on position: 0
Child: 1201202

Muted on position: 2
Child: 1211202

Crossover position: 6
X	: 2120202
Y	: 2022002
child	: 2120202

------------------------------------------------------------
Goal is found: 
Western Australia 		: BLUE
Northern Trritory 		: RED
South Australia 		: GREEN
Queens Land 			: BLUE
New South Wales 		: RED
Victoria 			: BLUE
Tasmia 				: BLUE
__________________________________________________________________________

<h2 align="center">Thank You </h2>


