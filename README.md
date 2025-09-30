## 📝 Java GUI – ToDo App

## 📌 Objective

Build a To-Do List application using Java Swing that allows users to add and delete tasks interactively.

---

## 🛠 Tools & Technologies

- Java

- Swing (built-in GUI library)

- IntelliJ IDEA CE or Eclipse

---

## 🚀 Features

- Add tasks to the list.

- Delete selected tasks.

- Scrollable task list.

- Simple and lightweight desktop application.

---

## 📂 Project Structure

- ToDoApp.java     # Main application file

---

## 📂 Project Structure in VS Code

ToDoAppProject/                # Your project root folder

│

├── .vscode/                   # VS Code settings (auto-generated)

│   ├── launch.json            # Debug configuration

│   └── settings.json          # Project settings

│

├── src/                       # Java source files

│   └── ToDoApp.java           # Your main class

│

└── bin/                       # Compiled .class files (auto-created)

---

## 💻 How to Run in VS Code

## ⚡ Step-by-Step Setup

1.Create Project Folder

- Make a folder called ToDoAppProject.

- Inside, create a folder named src.

2.Add Java File

- Inside src, create a file:

ToDoApp.java


- Paste the class code I gave you earlier.

3.Open in VS Code

- Open ToDoAppProject in VS Code.

- Install Java Extension Pack (if not done already).

4.Configure Build & Run

- VS Code will detect the .java file automatically.

- First time you run, it will generate a .vscode folder with launch.json.

Or manually build using terminal:

javac -d bin src/ToDoApp.java
java -cp bin ToDoApp


5.Run the Program

- Hit ▶ Run in VS Code (top-right corner).

- Or use terminal as above.

- A GUI window will appear.

---

## 💻 How to Run

- Open the project in IntelliJ IDEA CE or Eclipse.

- Compile and run the ToDoApp.java file.

- A window will appear where you can:

- Enter a task in the text field.

- Click Add Task to add it.

- Select a task and click Delete Task to remove it.

---

## 📸 Sample GUI Preview

- Main Window:

- Text field for entering tasks.

- Buttons: Add Task and Delete Task.

- List showing added tasks.

---

## 🎯 Outcome

By completing this project, you will:

- Gain hands-on experience in desktop GUI development with Java Swing.

- Learn how to handle events (ActionListeners) in Swing.

- Understand the use of JFrame, JButton, JTextField, JList, and DefaultListModel.

