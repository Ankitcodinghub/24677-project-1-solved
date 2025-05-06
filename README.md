# 24677-project-1-solved
**TO GET THIS SOLUTION VISIT:** [24677 Project 1 Solved](https://www.ankitcodinghub.com/product/24677-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96308&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;24677 Project 1  Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1 Introduction

This project will entail using Webots, an open-source robotics simulation software, to learn more about control methods for autonomous vehicles. Webots was chosen because of its ease of use, flexibility, and impressive rendering capability. A brief guide for Windows, Mac OS, and Linux follows. Please see the links on the previous page for a link to documentation and more information.

For Windows:

<ol>
<li>Download and install Webots R2021a.</li>
<li>Download and install Python natively from Python’s official webpage. 3.9 is recom- mended, but any version from 3.7 – 3.9 will work.</li>
<li>Open a Command Prompt window (right-click and select “Run as Administrator”). On the command line, install numpy, scipy, and matplotlib with the following command: python -m pip install &lt;package-name&gt;.</li>
<li>Ifyouencounterissuesinstallingmatplotlib,pleasetryupgradingpipandsetuptools:: python -m pip install –upgrade pip

python -m pip install –upgrade setuptools</li>
</ol>
For Mac:

<ol>
<li>Download and install Webots R2020b.</li>
<li>Download and install Python natively from Python’s official webpage. 3.8 is recom- mended, but 3.7 will also work.</li>
<li>In a Terminal window, install numpy, scipy, and matplotlib with the following com- mand:
pip3.x install &lt;package-name&gt;

where x is the version number you installed.
</li>
<li>Check where your Python is installed with:
<pre>     which python3.x
</pre>
Copy the path that appears and open Webots. In the Webots menu at the top, open Tools → Preferences, and paste the copied path under “Python command”.
</li>
</ol>
For Linux:

<ol>
<li>Download and install Webots R2021a.</li>
<li>In a terminal window, make sure you have numpy, scipy, and matplotlib with the following command:

pip install &lt;package-name&gt;.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
As you might already know, Buggy is a time-honored CMU tradition (you can learn more about it here and here). Unfortunately, it was not able to be held in-person this year due to the pandemic. To help make up for this, you will be asked to create a controller that helps a vehicle to complete the same course in simulation. However, instead of controlling an actual Buggy, you’ll be controlling a Tesla Model 3. It’s a bit more fun and stylish (we hope)!

We will follow the steps listed below to learn more about the system and synthesize several different kinds of controllers:

<ol>
<li>Examine the provided nonlinear control model</li>
<li>Linearize the state space system equations [P1]</li>
<li>Develop a PID controller for the system [P1]</li>
<li>Check the controllability and stabilizability of the system [P2]</li>
<li>Design a full-state feedback controller using pole placement [P2]</li>
<li>Design an optimal controller [P3]</li>
<li>Implement A* algorithm [P3]</li>
<li>ImplementanextendedKalmanfilter(EKF)forsimultaneouslocalizationandmapping (SLAM) [P4]</li>
</ol>
The project has been divided into 4 parts to reflect this:

<ol>
<li>P1 &nbsp;(a) Linearize the state space model

(b) Design a PID lateral and PID longitudinal controller</li>
<li>P2 &nbsp;(a) Check the controllability and stabilizability of the linearized system (b) Design a lateral full-state feedback controller</li>
<li>P3 &nbsp;(a) Design an lateral optimal controller

(b) Implement A* path planning algorithm</li>
<li>P4 &nbsp;(a) Implement EKF SLAM to control the vehicle without default sensor input (b) Race with other Buggy competitors in the class</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
2 Model

</div>
</div>
<div class="layoutArea">
<div class="column">
inertial

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Bicycle model [2]

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2: Tire slip-angle [2]

</div>
</div>
<div class="layoutArea">
<div class="column">
We will make use of a bicycle model for the vehicle, which is a popular model in the study of vehicle dynamics. Shown in Figure 1, the car is modeled as a two-wheel vehicle with two degrees of freedom, described separately in longitudinal and lateral dynamics. The model parameters are defined in Table 2.

2.1 Lateral dynamics

Ignoring road bank angle and applying Newton’s second law of motion along the y-axis: may =Fyf cosδf +Fyr

􏰀d2y􏰁

where ay = dt2

in the direction of the y axis, Fyf and Fyr are the lateral tire forces of the front and rear

</div>
</div>
<div class="layoutArea">
<div class="column">
is the inertial acceleration of the vehicle at the center of geometry

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
wheels, respectively, and δf is the front wheel angle, which will be denoted as δ later. Two terms contribute to ay: the acceleration y ̈, which is due to motion along the y-axis, and the centripetal acceleration. Hence:

a y = y ̈ + ψ ̇ x ̇

Combining the two equations, the equation for the lateral translational motion of the vehicle

is obtained as:

y ̈=−ψ ̇x ̇+m1(Fyf cosδ+Fyr)

Moment balance about the axis yields the equation for the yaw dynamics as

ψ ̈Iz =lfFyf −lrFyr

The next step is to model the lateral tire forces Fyf and Fyr. Experimental results show that the lateral tire force of a tire is proportional to the “slip-angle” for small slip-angles when vehicle’s speed is large enough – i.e. when x ̇ ≥ 0.5 m/s. The slip angle of a tire is defined as the angle between the orientation of the tire and the orientation of the velocity vector of the vehicle. The slip angle of the front and rear wheel is

αf =δ−θVf αr =−θVr

where θV p is the angle between the velocity vector and the longitudinal axis of the vehicle, for p ∈ {f, r}. A linear approximation of the tire forces are given by

􏰄 y ̇ + l f ψ ̇ 􏰅 Fyf=2Cα δ− x ̇

􏰄 y ̇−lrψ ̇􏰅 Fyr=2Cα − x ̇

where Cα is called the cornering stiffness of the tires. If x ̇ &lt; 0.5 m/s, we just set Fyf and Fyr both to zeros.

2.2 Longitudinal dynamics

Similarly, a force balance along the vehicle longitudinal axis yields:

x ̈ = ψ ̇ y ̇ + a x max = F − Ff

Ff =fmg

where F is the total tire force along the x-axis, and Ff is the force due to rolling resistance

at the tires, and f is the friction coefficient.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
2.3 Global coordinates

In the global frame we have:

2.4 System equation

</div>
<div class="column">
X ̇ =x ̇cosψ−y ̇sinψ Y ̇ =x ̇sinψ+y ̇cosψ

</div>
</div>
<div class="layoutArea">
<div class="column">
Gathering all of the equations, if x ̇ ≥ 0.5 m/s, we have:

</div>
</div>
<div class="layoutArea">
<div class="column">
2 C 􏰄 y ̇ + l ψ ̇ 􏰅 y ̈=−ψ ̇x ̇+α(cosδδ− f − r)

</div>
</div>
<div class="layoutArea">
<div class="column">
y ̇ − l ψ ̇ m x ̇ x ̇

</div>
</div>
<div class="layoutArea">
<div class="column">
x ̈ = ψ ̇y ̇ + m1 (F − fmg)

2lC􏰄 y ̇+lψ ̇􏰅2lC􏰄y ̇−lψ ̇􏰅

</div>
</div>
<div class="layoutArea">
<div class="column">
ψ ̈= f α δ− f − r α − r Iz x ̇ Iz x ̇

</div>
</div>
<div class="layoutArea">
<div class="column">
X ̇ =x ̇cosψ−y ̇sinψ Y ̇ =x ̇sinψ+y ̇cosψ

otherwise, since the lateral tire forces are zeros, we only consider the longitudinal model.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.5 Measurements

The observable states are:

2.6 Physical constraints

The system satisfies the constraints that:

</div>
</div>
<div class="layoutArea">
<div class="column">
 x ̇ 

 y ̇ 

  ψ ̇   y = X  Y 

ψ

</div>
</div>
<div class="layoutArea">
<div class="column">
|δ|􏰆π6 rad

F 􏰇0andF 􏰆15736N x ̇ 􏰇 10−5 m/s

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Name

δ or δf F

m

Cα Iz

Fpq

f delT

</div>
<div class="column">
Table 1: Model parameters. Unit

</div>
</div>
<div class="layoutArea">
<div class="column">
Description

Front wheel angle Total input force Vehicle mass

Cornering stiffness of each tire Yaw intertia

Tire force, p ∈ {x, y},q ∈ {f, r} Rolling resistance coefficient Simulation timestep

</div>
<div class="column">
rad N kg

N

kg mˆ2 N

N/A sec

</div>
<div class="column">
Value

State Input 1888.6

20000

25854

Depends on input force 0.019

0.032

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
(x ̇, y ̇)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Vehicle’s velocity along the direction of vehicle frame

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
m/s

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
State

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
(X,Y)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Vehicle’s coordinates in the world frame

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
m

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
State

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
ψ , ψ ̇

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Body yaw angle, angular speed

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
rad, rad/s

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
State

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
lr

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Length from rear tire to the center of mass

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
m

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1.39

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
lf

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Length from front tire to the center of mass

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
m

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1.55

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
3 Resources 3.1 Simulation

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: Simulation code flow

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Several files are provided to you within the controllers/main folder. The main.py script initializes and instantiates necessary objects, and also contains the controller loop. This loop runs once each simulation timestep. main.py calls your controller.py’s update method on each loop to get new control commands (the desired steering angle, δ, and longitudinal force, F). The longitudinal force is converted to a throttle input, and then both control commands are set by Webots internal functions. The additional script util.py contains functions to help you design and execute the controller. The full codeflow is pictured in Figure 3.

Please design your controller in the your controller.py file provided for the project part you’re working on. Specifically, you should be writing code in the update method. Please do not attempt to change code in other functions or files, as we will only grade the relevant your controller.py for the programming portion. However, you are free to add to the CustomController class’s init method (which is executed once when the CustomController object is instantiated).

3.2 BaseController Background

The CustomController class within each your controller.py file derives from the Base- Controller class in the base controller.py file. The vehicle itself is equipped with a Webots-generated GPS, gyroscope, and compass that have no noise or error. These sensors are started in the BaseController class, and are used to derive the various states of the vehicle. An explanation on the derivation of each can be found in the table below.

</div>
</div>
<div class="layoutArea">
<div class="column">
Name (X, Y ) (x ̇,y ̇) ψ

ψ ̇

3.3 Trajectory Data

</div>
<div class="column">
Table 2: State Derivation. Explanation

From GPS readings

From the derivative of GPS readings From the compass readings

From the gyroscope readings

</div>
</div>
<div class="layoutArea">
<div class="column">
The trajectory is given in buggyTrace.csv. It contains the coordinates of the trajectory as (x, y). The satellite map of the track is shown in Figure 4.

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
4 P1: Problems

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 4: Buggy track[3]

</div>
</div>
<div class="layoutArea">
<div class="column">
Exercise 1. Model Linearization. As mentioned in class, model linearization is always the first step for non-linear control. During this assignment, you will approximate the given model with a linear model.

Since the longitudinal term x ̇ is non-linear in the lateral dynamics, we can simplify the controller by controlling the lateral and longitudinal states separately. You are required to write the system dynamics in linear forms as s ̇1 = A1s1 + B1u and s ̇2 = A2s2 + B2u in terms of the following given input and states:

y

􏰂δ􏰃 y ̇ 􏰂x􏰃

u = F , s 1 =  ψ  , s 2 = x ̇ 

ψ ̇

Assume that for values of x ̇ &lt; 0.5 m/s that the system is identical, i.e. there is no need to linearize two separate systems.

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Exercise 2. Controller Synthesis in Simulation. The driver functions that control the car take the desired steering angle δ and a throttle input – ranging from 0 to 1 – which is derived from the desired longitudinal force F .

For this question, you have to design a PID longitudinal controller and a PID lateral con- troller for the vehicle. A PID is an error-based controller that requires tuning proportional, integral, and derivative gains. As a PID allows us to minimize the error between a set point and process variable without deeper knowledge of the system model, we will not need our result from Exercise 1 (though it will be useful in future project parts).

Design the two controllers in your controller.py. You can make use of Webots’ built- in code editor, or use your own.

Check the performance of your controller by running the Webots simulation. You can press the play button in the top menu to start the simulation in real-time, the fast-forward button to run the simulation as quickly as possible, and the triple fast-forward to run the simulation without rendering (any of these options is acceptable, and the faster options may be better for quick tests). If you complete the track, the scripts will generate a performance plot via matplotlib. This plot contains a visualization of the car’s trajectory, and also shows the variation of states with respect to time.

Submit your controller.py and the final completion plot as described on the title page. Your controller is required to achieve the following performance criteria to receive full points:

<ol>
<li>Time to complete the loop = 400 s</li>
<li>Maximum deviation from the reference trajectory = 10.0 m</li>
<li>Average deviation from the reference trajectory = 5 m</li>
</ol>
Some hints that may be useful:

<ul>
<li>Using a PID controller requires storing variables between method calls. Python allows this through use of the self preface (in other words, making them class member variables). Think about which variables you use in your controller that you will need to store, and be sure to add them to CustomController’s init method so they are initialized.</li>
<li>If you are tuning your lateral controller for a point on the trajectory that is the closest to the vehicle, the controller may struggle on sudden turns. Think about how to add some mechanism that “looks ahead” of your current position before calculating a control command.</li>
<li>Functions in util.py might be useful. For example, closestNode returns the absolute value of the cross-track error, which is the distance from the vehicle’s center of gravity to the nearest waypoint on the trajectory. In addition, the function also returns the index of the closest waypoint to the vehicle.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
• If your car does not perform well, it may just be that it requires tuning. You may al- ready have some experience tuning PID controllers, but if not, viewing online resources is recommended. See this Wiki link [4] for more background in the process of manual tuning.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
5 Reference

<ol>
<li>Rajamani Rajesh. Vehicle Dynamics and Control. Springer Science &amp; Business Media, 2011.</li>
<li>Kong Jason, et al. “Kinematic and dynamic vehicle models for autonomous driving control design.” Intelligent Vehicles Symposium, 2015.</li>
<li>cmubuggy.org, https://cmubuggy.org/reference/File:Course_hill1.png</li>
<li>“PID Controller – Manual Tuning.” Wikipedia, Wikimedia Foundation, August 30th,
2020. https://en.wikipedia.org/wiki/PID_controller#Manual_tuning
</li>
</ol>
</div>
</div>
</div>
