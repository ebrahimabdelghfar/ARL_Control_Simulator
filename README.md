# ARL_Control_Simulator
<p align="center">
  <img width="100" src="https://github.com/ebrahimabdelghfar/ARL_Control_Simulator/assets/81301684/518dde34-0b12-4f90-ade0-7b43214612ea">
  <img width="300" src="https://github.com/ebrahimabdelghfar/ARL_Control_Simulator/assets/81301684/43bae450-61cc-4866-8bd8-4601ac332594">
</p>

## Objective 
The Objective of this simulator to act as learning platform for the ARL workshop to make the student apply their algorithim for path tracking and pendulum balancing
## Topics 
```
/CarVel # used to publish the car position relative to the world in meter
  # Msg_Type: geometry_msgs/msg/Vector3

/CarOdom # used to publish the car position relative to the world in meter/sec
  # Msg_Type: geometry_msgs/msg/Vector3

/PendulumAngle # used to publish the pendulum angle position in rad
  #Msg_Type: std_msgs/msg/Float64

/PendulumAngleVel #used to publish the pendulum angle position in rad/sec
  #Msg_Type: std_msgs/msg/Float64

/SteeringAngle #used to subscribe the steering angle position in rad
  #Msg_Type: std_msgs/msg/Float64

/cmd_torque #used to publish the motor velocicty position in rad/sec
  #Msg_Type: std_msgs/msg/Float64
```
