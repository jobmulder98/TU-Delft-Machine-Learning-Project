# Robotics TU Delft - Machine Learning Project
- Course: Machine Learning for Robotics 
- Programming Language: Python
- Grade: 7.5
- File to run: 63_final_assignment

# Project Description 
In this assignment a fellow student and I treated the problem of a supervised classification task for a car that has to find its way along a racing track on different
planets. The training input (observations) and output (action labels) data were be obtained through demonstrations of humans manually controlling 
the robot car. By training machine learning models on these demonstrations, I created an AI which "imitates" how a human would drive. There were some 
coding challenges and design choices that I had to solve to use human driving demonstrations as labeled data to create the machine learning models. 
Unfortunately, in the end the car couldn't finish the track on each planet. However, with some extra time and effort the algorithm could be improved. 

# Installation Instructions
1. Download the repository for the environment [here](https://github.com/ageron/handson-ml2/archive/master.zip).
2. Extract the folder on the Desktop (or in the preferred directory)
3. Open Anaconda Prompt (Anaconda3) from the Start menu
4. In the terminal use cd and the directory where did you extracted the folder of the handson-ml2 (for example cd Desktop/handson-ml2)
5. Type conda env create -f environment.yml
6. Type ```conda activate tf2```
7. Type ```conda install pywin32=227```
8. Type ```python -m ipykernel install --user --name=python3```
9. Type ```jupyter notebook```
10. Extract the demonstrations.zip file

You are ready to go!
