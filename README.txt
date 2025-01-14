Lazy Balanced Tree Program

A C++ application that stores and manages student and faculty data in a lazily balanced binary search tree. When the height ratio of the root’s subtrees exceeds 1.5, the tree automatically rebuilds to maintain efficient queries. It also provides a user-friendly interface for adding data and performing a variety of operations to view or modify records.

Requirements
1. A C++ compiler (e.g., g++)
2. A terminal or IDE that supports C++ compilation

Setup Instructions
1. Clone or download this program to your local system.
2. Ensure all source files (e.g., BST.h, TreeNode.h, DataBase.cpp, etc.) are in the same directory.
3. Compile using:
g++ *.cpp -o main
4. This will create an executable named `main` (or `main.exe` on Windows).

How to Run
1. Open a terminal and navigate to the directory containing the compiled program.
2. Run the program:
  ./main
3. Follow the on-screen instructions to:
- Add student or faculty records.
- Perform queries to retrieve or update existing data.
- Observe automatic rebalancing when the left and right subtree height ratio exceeds 1.5.

Program Features
1. Dynamic Tree Balancing:
- Automatically rebuilds the tree when a significant height imbalance occurs (ratio > 1.5).
2. Two Data Types:
- Stores Student and Faculty objects with unique attributes (e.g., IDs, names).
3. Multiple Operations:
- Allows a variety of queries and manipulations (e.g., add/remove student/faculty, link advisors, print records, etc.).
4. User-Friendly Interface:
- Text-based menu prompts for easy data entry and command execution.

Troubleshooting
- Ensure you have a valid C++ compiler installed and the necessary permissions to run executables.
- If you encounter issues with student-faculty references, make sure you create faculty entries before linking students’ advisor IDs.

License
This project was developed by Luke Morissette. Feel free to use, modify, and share it with attribution or under any additional terms specified in this repository.
