🌲 Binary Search Tree (BST) Console Application
A simple yet powerful C++ console application that implements a Binary Search Tree (BST) with functionality for insertion, deletion, and post-order traversal. Perfect for learning data structures or using as a foundational component in more complex systems.

Project Structure
├── BinarySearchTree.h    # BST class declaration
├── BinarySearchTree.cpp  # BST class implementation
├── main.cpp              # User interface for BST operations
├── tasks.json            # Build configuration for VS Code

 Features
✅ Insert new integers into the BST
✅ Delete specific values from the tree
✅ Print the tree in post-order traversal
✅ Interactive console-based menu system

Implementation Highlights
1) Fully dynamic memory management (no memory leaks)
2) Uses recursive functions for insertion, deletion, and traversal
3) Cleanly separated interface (.h) and implementation (.cpp)
4) Follows good object-oriented design principles

🔧 How to Build and Run
✅ Prerequisites
C++ Compiler (like g++)

Optional: Visual Studio Code for using tasks.json

🛠️ Build with Command Line
bash
Copy
Edit
g++ main.cpp BinarySearchTree.cpp -o bst_app
./bst_app
🧱 Or Build with VS Code
Open folder in VS Code

Press Ctrl+Shift+B to build using the Tasks system

Run the generated executable

📸 User Interface Preview
markdown
Copy
Edit
 Binary Search Tree Operations 
 ----------------------------- 
 1. Insertion/Creation 
 2. Printing 
 3. Removal 
 4. Exit 
 Enter your choice :


📌 Notes
Post-order traversal prints nodes in Left → Right → Root order.
Tree nodes are automatically managed and deleted via the class destructor.
Menu runs in a continuous loop until you choose to exit.

👨‍💻 Author
Created by Akshat Sonker.






