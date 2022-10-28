# Fitness-Simulation
Repository for group project, the fitness simulation.

Fitness Simulation

Demonstrating code reuse through Inheritance and Polymorphism
I hope you’ll find the project to be both educational and entertaining.
In this project you will be doing a (albeit a bit quirky) life simulation, with the ultimate goal of increasing 
fitness.  
The fictious person in the program starts with a little bit of money, some strength, and a few days’ 
worth of energy (measured in calories).   The user of your program gets to control what the fictitious 
person does.  They user can have the fictious person:
 Acquire a skill which allows them to perform an activity
 Setup their calendar to specify which activity they do during each day of the week
In order to perform an activity, the person must first acquire the corresponding skill.  Some skills can be 
acquired for free (e.g. eating, working at a store, or doing sit-ups) whereas other skills have a cost 
associated with them (e.g. to work in tech, you need to pay for college, or to do weight lifting, you need 
to purchase weights).  
Each activity has some benefits (eating increases energy/calories, exercising on the elliptical increases 
your fitness level, and lifting weights increases your strength) and some costs (running burns some 
muscle mass decreasing your strength & energy).  Also, some activities have a daily cost or benefit.  For 
example, working in a store pays a daily salary of $120, whereas using an elliptical, costs $4 per day for 
maintenance.  Similarly, each daily activity can either increase or decrease your strength.  If the fictitious 
person does not have enough money or strength to perform the activity on the scheduled day, the 
activity will be skipped and the fictitious person will not receive any of the benefits for the activity.
This table details the costs and benefits of each activity:

Activity      (Fitness Increase) (Wealth Change) (Strength Change) (Calories gained or consumed) (Skill Cost)

Work at store         -5               120               -1                     -1000                     0
Work in tech         -30               250                0                      -750                  1000
Run (you'll need 
to buy shoes)         10                -3               -2                      -300                   100
Sit-ups                4                 0                2                      -100                     0
Elliptical            20                -4               -1                       -60                  1500
Weight lift           10                -5               20                       -50                   250
Eat                    0               -40               -1                      2000                     0

Program Structural Requirements
We’ll design the project during class, and setup the structural requirements.

Grading Rubric
Item Points
User interface / Menu 10
Maintaining Schedule 10
Maintaining Skillset 10
Correctly preventing activities that haven't met the requirements 10
Running Weekly Simulation and correctly updating person values 10
Proper use of Inheritance 10
Proper use of polymorphism / virtual functions 10
Properly displaying the fictitious persons stats 10
Correctly ending the program once a fitness level of 100 is achieved 10
Overall code quality 10
Total 100
