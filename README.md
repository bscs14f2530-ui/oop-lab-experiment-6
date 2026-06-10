🏠 Room Width Program (C++ - Friend Function)
📌 Description

This is a simple C++ program that demonstrates the concept of a friend function. It allows an external function to access private data of a class (Room) and display the width of a room.

🧾 Features
Uses a class (Room) with private data
Demonstrates friend function concept
Allows external function to access private member
Simple object creation and display
🛠️ Technologies Used
C++
Object-Oriented Programming (OOP)
Friend Function concept
📂 Program Structure
Class Used
class Room {
private:
    double width;
};

The width variable is private and cannot be accessed directly outside the class.

🤝 Friend Function
friend void printWidth(Room r);
printWidth() is declared as a friend function
It can access private data of the class
Friend Function Definition
void printWidth(Room r) {
    cout << "Width of the room is: " << r.width << endl;
}
▶️ How It Works
A Room object is created.
Width is set using setWidth() function.
The friend function printWidth() is called.
It directly accesses and prints the private variable width.

myRoom.setWidth(10.10);
📤 Sample Output
Width of the room is: 10.1
