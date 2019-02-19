# Legged-Robot

This the final project implemented during the course of Legged Robot in EPFL, including kinetic and dynamic modeling of a biped walking robot.

To run the simulation of walking robot, please go to main.m in our main folder. 
To get different walking velocities, please go to control_hyper_parameter.m in the control folder. The parameters needed for the velocity of 0.4, 0.6, 0.8, 1.0, 1.2 and 1.5m/s have been given. When running code of specific velocity, just uncomment the parameters corresponding to other velocities. The defaulted parameters are for the lowest speed (0.4m/s). To observe the discrete average velocity in each step instead of the continuous curve of v_h, you can check the command in matlab, which will output the average velocity in each step. 

To add perturbation to the robot, please go to the control.m in the control folder, and uncomment this line of code : u_ext = perturbation(q, step_number). The plots for analysis will be shown according to analyze.m and analyze_2.m. If you want to observe the each plot more clearly, use the line of code in main.m analyze_2(sln). If you want to have a more intuitive observation of all plots, please run the following code: analyze(sln)
