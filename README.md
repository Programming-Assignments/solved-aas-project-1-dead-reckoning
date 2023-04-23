Download Link: https://assignmentchef.com/product/solved-aas-project-1-dead-reckoning
<br>
<span class="kksr-muted">Rate this product</span>

This short project is composed by problems which are useful as a training session, for preparing you for projects during subsequent weeks in AAS.

Problem 1

Given the following approximate model of a pendulum,

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/446.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/446.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

 ( t ) = − A  s i n ( ( t ) ) − B   ( t ) + C  u ( t ) A=110rad, B=2.21, C=1.1 rad

s2 s s2 voltwhere (t)is the angular position (expressed in radians) of the pendulum, and u(t)is the voltage (expressed in volts)

controlling the pendulum’s electric motor.a) Obtain a valid state space representation for this system, in continuous time.b) Obtain an approximate discrete time model (using Euler’s approximation), for a sample time dt=1ms. c) Implement a program (in plain Matlab language), for simulating the model proposed in (b).

Test your program simulating the following cases:c.1) The pendulum is released, at time =0, having the following initial conditions: angular velocity =0 and angle = 110 degrees. The voltage of the electric motor is assumed to be constantly 0 volts (no torque being applied by the motor).c.2) Similar to (c.1) but having the electric motor controlled with a constant voltage = 3 volts.

In both cases, perform the simulation for an interval of time from 0 to t=7 seconds. Plot the results (position and angular velocity) in a figure.

d) Using the model implemented in item c, implement a simulation in Simulink.

Problem 2

Given the following simplified 3DoF kinematic model (of a car-like wheeled platform),

x(t)=v(t)cos((t)) y(t)=v(t)sin((t))

 (t ) = tan ( (t )) v (t ) L

<ol>

 <li>a)  Obtain an approximate discrete-time version of the model, assuming small discrete steps, e.g. of dt=0.01 seconds(10ms). Consider the case of a vehicle that has L=2.5m.</li>

 <li>b)  Implement a program for simulating the system in (a). Run it under different steering actions (sequences ofsteering angles  (k ) ) and assume constant speed, v (k ) = 3.5 m/s, k . c.1) See what happen if you keep the steering angle set at a constant value.c.2) Try to generate a path having an 8-shape (define a proper sequence of control actions to achieve it).</li>

</ol>

Advanced Autonomous Systems–Project 0 (training). Version 2021.1 . 1

c.4) Apply a small modification on the model (e.g. a small change in parameter L) and see how the result is affected, for a long-term simulation (for cases c.1 and c.2). Plot, jointly, both models’ trajectories using different colors, to appreciate the different responses.

Note: The main purpose of this task is to give the students some initial training, before the actual projects are released. This task is intended to be solved during week 1.