# Master-Project
This was a project realized by Guillaume Lorthioir and myself, Nicolas Billod, during our first year of Master in Computer Science in 2017, at the UPMC, Paris.

Development of a control architecture for a mobile robot (Thymio II) implemented in C, including an exploration module based on the A\* algorithm. To make all this work on the robot we used a Raspberry Pi 3 because it didn't have enough memory.
Thymio II robots have their own language ("Aseba") but luckily they have an interface ("Asebamellua") allowing D-Bus communication. So, to communicate with it we had to use the GDBus library.

You can see some videos illustrating what we get at the end :
- Robot doing a square, following orders : https://youtu.be/VANYIlAiHzA
- Robot looking for a path to a goal : https://youtu.be/7h7fRFxBJPg
- Robot doing an exploration : https://youtu.be/p6OsYIYKi4o
