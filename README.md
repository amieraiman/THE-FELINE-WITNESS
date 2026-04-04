Assignment 2 TEB 1043 Object Oriented Programming  (THE FELINE WITNESS)
__________________________________________________

Brief Description:

This GitHub repository contains the implementation for Assignment 2, serving as a functional prototype for our group project which is The Feline Witness. Developed entirely in C#, this menu driven, console-based interactive fiction game places the player in the unique perspective of a household cat.

After witnessing a suspicious encounter, the cat discovers the husband is conducting a secret affair while the wife is away. The ultimate goal is for The Feline Witness is the protagonist must try to disrupt the husband's plans such as by stealing and hiding his car keys and eventually finding a way to expose the truth to the wife.

__________________________________________________

Group members: 

Ahmad Zafran Bin Faizal (24005345)

Muhammad Wafi Bin Azman (24005379)

Muhammad Asyraaf Bin Mustafa (24005305)

Lee Xin Yue (24005697)

Humaira Rayyan Binti Haslah (24005364)

Amier Aiman Bin Mohamad Faizal (24005402)

__________________________________________________

1.0 Project Description:

This project is developed for Assignment 2 in the Object-Oriented Programming course. It work as a standalone simulation that come from our main project, and it is created to show the basic OOP concepts which is encapsulation and object interaction. To fulfill the requirement, the system uses the Character, HouseSpace, and Item classes based on our original UML design.

In this mini game, the player control a very observant house cat that is investigating its owner, the husband. The cat notice the husband acting suspicious with his smartphone in the living area, so it need to find his exact location to discover the truth. The simulation end successfully when the player identify Sofa 2 in the Living Room as the correct target. The gameplay focus on exploration and movement, where player can navigate through different HouseSpace objects and inspect Item objects inside it, allowing a smooth flow of data between the objects.

__________________________________________________

2.0 System Features:

*Interactive Spatial Navigation:*

The game features a room-to-room "travel" system. Players can input the 'C' command to view available rooms and move the main character between different HouseSpace objects (such as Bedroom, Kitchen, Living Room). The system securely updates and tracks the character's location using OOP properties.


*Environment Exploration & Object Interaction:*

By using the 'E' command, the project will reveal a list of 'Item' objects present in that specific room. Selecting an item triggers an interaction sequence where the system evaluates if the selected object is the target item (Sofa 2), which shows dynamic object-to-object communication.


*House Map Interface:*

Players can press 'M' at any point during the exploration phase to pull up an ASCII-art map of the house. This feature aids players in visualizing the layout of the HouseSpace objects and planning their next move.


*Custom Text Rendering Engine:*

To enhance the console-based user experience, the project has a custom 'delayedText' method. This method prints text character-by-character to simulate real-time typing, complete with customizable reading speeds and ANSI color codes for different contexts. Players can also skip the typing delay by pressing any key.


*Encapsulated State Management:*

True to the assignment's core requirement, the system strictly protects its data. Sensitive variables, such as a room's item list or a character's current location, are stored in private fields and accessed solely through public properties or controlled methods.
