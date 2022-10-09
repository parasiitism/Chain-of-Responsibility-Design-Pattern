# Chain-of-Responsibility-Design-Pattern

An overview of the Chain of Responsibility design pattern & its implementation with a real-world scenario!
![image](https://user-images.githubusercontent.com/86511874/194764035-1cec3cf6-1ac3-46c0-9992-840ba9298587.png)


📍 Chain of Responsibility Design Pattern is a Behavioral design pattern.

📍 The chain of responsibility pattern is mostly used to pass the responsibility to the next if the current object cannot handle it at the moment. By utilizing this Chain of Responsibility Design Pattern, you can accomplish the loose coupling.

Let’s understand this design pattern with the below example:

Assume that you need to control a menu on the user level. There you have the CEO, Director, Manager, and the Executives. So accordingly each of them has multiple levels of permissions. So if you need to implement something based on these particular levels of permission, you could use this design pattern.

The best example for the chain of a responsibility design pattern that is implemented at the practical level is the Java API logger.

When to use Chain of Responsibility? 🙄
🔥 We can use the Chain of Responsibility design pattern when our program is looking for a process in different types of requests in various approaches, but the exact kind of requests & the sequences of them are unspecified beforehand.

🔥 Can use this pattern if want to change the set of handlers & their order at runtime.

🔥 We can use this pattern when we want to execute some handlers in a certain order.

The most important fact here is, this design pattern encourages loosely coupled.

Example: The sender doesn't know who the receiver is and the receiver doesn't know who the sender is. Also, the sender can perform their job without knowing who will receive the message and at the same time, the receiver can perform their job without knowing the sender. So that means we can decouple the sender and the receiver by using this design pattern.

![image](https://user-images.githubusercontent.com/86511874/194764090-6a170738-136e-4ac6-8285-f42a4b0befe3.png)

![image](https://user-images.githubusercontent.com/86511874/194764096-c4bc72b2-a9cb-429d-8db5-c1bf7618ddbe.png)

Class diagram of the Chain of Responsibility design pattern


![image](https://user-images.githubusercontent.com/86511874/194764120-0f6a7f0e-161f-454b-bb3d-e0be71a1bd50.png)

Sequence diagram of the Chain of Responsibility design pattern

![image](https://user-images.githubusercontent.com/86511874/194764138-3963a0af-dbb6-4b63-ba37-e3132a11a4ad.png)
