# Console Output Basics (Task #1)

## 📌 Description
This is a foundational Java project designed to demonstrate basic console output operations. The goal of the task is to correctly use standard output streams to display mixed data types (integers and Unicode characters) on separate lines.

## 🚀 Task Requirements
The application must satisfy the following criteria:
1.  Print the current year: **2025**.
2.  Print a specific emoji: **😅** (Smiling Face with Open Mouth and Cold Sweat).
3.  Ensure each output is displayed on a **new line**.
4.  Strictly use the `System.out.println()` method for output operations.

## 🛠 Technical Stack
- **Language:** Java 23
- **IDE:** IntelliJ IDEA
- **Concepts covered:** Standard Output, String Literals, Unicode support in Java.

## 💻 Implementation Detail
In Java, emojis can be represented directly in a string literal or by using their Unicode escape sequence (`\ud83d\ude05`). This project ensures proper encoding handling for modern character sets.

```java
public class Task_1_App {
    public static void main(String[] args) {
        System.out.println(2025);
        System.out.println("\ud83d\ude05"); // Unicode for 😅
    }
}
```

## ⚖️ License
This project is licensed under the **MIT License**.

Copyright (c) 2025 Yurii Pavlenko

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files...

License: [MIT](LICENSE)
