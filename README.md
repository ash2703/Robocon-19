# Robocon-19
Robocon is an **International level robotics competition** hosted by ABU. **Robocon 19 was hosted by Mongolia** with the challenge to develop 2 autonomous robots amongst which 1 was a **Quadruped Robot**.


We designed an **autonomous quadruped bot** inspired from the anatomy of a horse.
           
           
<p align="center">         
<img src="images/best-bot.PNG">
</p>

4 legs of the bot consists of 8 revolute joints i.e. each leg consists of 2 revolute joints. Revolute action is performed with the help     of digital servos capable of rotating 0-120 degrees precisely.

All the 4 legs are attached symmetrically to a solid frame such that the CG (centre of gravity) of the system lies in the centre of the     frame and also the CG lies inside the triangle formed by 3 joints when a leg is suspended for the bot to be dynamically stable.

**Trot Gait**
The bot is made dynamically stable using quadruped gait for higher speed and dynamic stability. Trot Gait is used similar to the motion of a horse. Two diagonal legs swings forward while other two support the body and move backward. The speed of the bot is decided by the frequency of raising and pushing the legs of the bots. More the speed, more is the stability.

**Rotary actuators**
8 digital servos **(CYS8218->36kgcm 0.18sec/60 degree,4us dead-band)**, each are used to provide revolute action at the joints of legs. Digital servos provide better resolution at higher precision angles, faster response and constant torque. All the servos are connected to a single micro-controller (AtMega2560) which controls the servos simultaneously using various algorithms.

