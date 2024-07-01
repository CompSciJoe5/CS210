# CS210
CS210 Programming Languages


Project Title: Clock Application
Project Summary
The project is a Clock application that displays time in both 12-hour and 24-hour formats and allows users to increment the hour, minute, and second. The primary problem it solves is providing a simple, user-interactive clock that can be easily manipulated to display time in two common formats. This application is useful for understanding basic time-keeping and manipulation functions.

Reflection
Summarize the project and what problem it was solving
This Clock application project addresses the need for a user-interactive clock that can display time in both 12-hour and 24-hour formats. The problem it solves is providing a straightforward way for users to view and manipulate time, making it a useful tool for educational purposes or simple time-keeping tasks.

What did you do particularly well?
I did particularly well in designing the class structure and implementing the functionality for both 12-hour and 24-hour time formats. The Clock class is well-encapsulated, and the methods for adding hours, minutes, and seconds are logically structured and easy to understand. Additionally, the display functions are formatted to ensure time is presented in a clear and user-friendly manner.

Where could you enhance your code?
There are several enhancements that could be made:

Optimization: The addHour, addMinute, and addSecond methods could be optimized further to reduce redundancy.
Input Validation: Adding input validation to ensure that the user inputs valid choices would enhance the program's robustness.
Error Handling: Implementing more comprehensive error handling would make the application more secure and reliable.
These improvements would make the code more efficient and secure by ensuring it handles unexpected inputs and conditions gracefully.
Which pieces of the code did you find most challenging to write, and how did you overcome this?
The most challenging part of the code was managing the wrapping of hours, minutes, and seconds correctly, especially ensuring that the 12-hour format correctly displays "AM" and "PM". To overcome this, I utilized modular arithmetic and carefully tested edge cases to ensure the transitions were handled correctly. Online resources and C++ documentation were invaluable in understanding and implementing these time calculations.

What skills from this project will be particularly transferable to other projects or coursework?
Skills gained from this project that are transferable include:

Class Design and Implementation: Understanding how to design and implement a class in C++.
Time Manipulation: Knowledge of how to manipulate and format time.
User Interaction: Handling user input and implementing a simple menu system.
These skills are applicable to any project that involves class-based design, user interfaces, or time-related functionalities.
How did you make this program maintainable, readable, and adaptable?
To ensure the program is maintainable and readable:

Code Documentation: I included comments and followed a consistent naming convention.
Modular Design: The Clock class encapsulates all time-related functionality, making it easy to maintain and extend.
Readable Output: The display functions use formatting to present the time clearly.
Flexibility: The program is designed to be adaptable to different time formats and easy to modify for additional features.


Repository Link

https://github.com/CompSciJoe5/CS210.git
