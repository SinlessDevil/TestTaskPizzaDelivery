🎮 Pizza Delivery — Test Task DevHub Game
<p align="center"> <a href="https://www.youtube.com/watch?v=MobLlsnx6Xg&t=13s" target="_blank"> <img src="https://img.youtube.com/vi/MobLlsnx6Xg/0.jpg" alt="Watch the demo" /> </a> </p> <p align="center"> <a href="https://www.youtube.com/watch?v=4GVzAM5tUFs&t=13s" target="_blank"> <img src="https://img.shields.io/badge/Watch%20on-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube" /> </a> </p>

Test task for the position
"Unity Developer"

Task: create from geometric primitives available in the
unity editor or from any assemblies, to make a prototype of a game about
pizza delivery.

The player plays as a cyclist who rides forward on the road. In the middle of the
of the screen the player has a circular joystick control, rotating the joystick
to the right, the player pedals faster, so he rides faster,
turning the pedals in the opposite direction slows the player down. Since
player rides on the road he can be hit by cars (any obstacles),
that can pop out from around corners. Some kind of analogue of Crossy Road.
Reaching point N, the player throws a pizza to the customer (conditional
cylinder).

![Image alt](https://github.com/SinlessDevil/Test_task_PizzaDelivery/blob/main/ScreenShots/GamePlay_PizzaDelivery_1.png)
![Image alt](https://github.com/SinlessDevil/Test_task_PizzaDelivery/blob/main/ScreenShots/GamePlay_PizzaDelivery_2.png)

In this test task I used the following patterns

Pattern Object Pooling: where you pre-instantiate all the objects you’ll need at any specific moment before gameplay — for instance, 
during a loading screen. Instead of creating new objects and destroying old ones during gameplay, your game reuses objects from a “pool”.

![Image alt](https://github.com/SinlessDevil/Test_task_PizzaDelivery/blob/main/ScreenShots/Pool_Mono_Task_PizzaDeviler.png)
![Image alt](https://github.com/SinlessDevil/Test_task_PizzaDelivery/blob/main/ScreenShots/Pool_Mono_Task_PizzaDeviler_1.png)

Pattern Singleton: is a creational design pattern, 
which ensures that only one object of its kind exists and provides a single point of access to it for any other code.

![Image alt](https://github.com/SinlessDevil/Test_task_PizzaDelivery/blob/main/ScreenShots/Singletone_Task_PizzaDeviler.png)

Pattern Observer: is a behavioral design pattern that allows some objects to notify other objects about changes in their state.
Usage examples: The Observer pattern is pretty common in C# code, especially in the GUI components. It provides a way to react 
to events happening in other objects without coupling to their classes.

![Image alt](https://github.com/SinlessDevil/Test_task_PizzaDelivery/blob/main/ScreenShots/Observer_Task_PizzaDeviler.png)
