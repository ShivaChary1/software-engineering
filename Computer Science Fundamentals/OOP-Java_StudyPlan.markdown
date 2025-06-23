# 2-Month Study Plan for OOP in Java (3 Days/Week)

This plan is designed to master Object-Oriented Programming (OOP) in Java over 2 months, studying 2 hours per day, 3 days per week (Monday, Wednesday, Friday), totaling ~48 hours. The schedule is structured for Notion dashboard integration, with weekly topics, learning objectives, tasks, and resources. The plan covers core OOP concepts, essential advanced topics, and practical projects, condensed to fit the reduced study time.

## Plan Overview
- **Duration**: 8 weeks, 3 days/week (Mon, Wed, Fri), 2 hours/day.
- **Total Hours**: ~48 hours (6 hours/week × 8 weeks).
- **Structure**: Each week includes theory (videos/books), practice (coding exercises), and mini-projects. Some weeks use a third day for review or project work.
- **Notion Integration**: Use a table in Notion with columns for Week, Day, Topic, Learning Objective, Tasks, Resources, and Status (e.g., To Do, In Progress, Done).
- **Prerequisites**: Basic Java knowledge (variables, data types, loops, conditionals, methods).
- **Goal**: Gain proficiency in OOP principles (encapsulation, inheritance, polymorphism, abstraction) and apply them in Java projects.

## Weekly Study Plan

### Week 1: Classes and Encapsulation
**Goal**: Understand classes, objects, and encapsulation.
- **Total Hours**: 6 hours
- **Topics**: Classes, Objects, Constructors, Encapsulation
- **Learning Objectives**:
  - Define and instantiate classes and objects.
  - Use constructors to initialize objects.
  - Implement encapsulation with access modifiers.
- **Schedule**:
  - **Monday (2h)**: Classes and Objects
    - Watch: [Java OOP Tutorial by freeCodeCamp](https://www.youtube.com/watch?v=1qG2xNrfcqM) (0:00-0:20).
    - Read: [Oracle Java Tutorials - Classes](https://docs.oracle.com/javase/tutorial/java/javaOO/classes.html).
    - Task: Write a `Student` class with fields (name, id) and a method to display details. Create objects in a main method.
  - **Wednesday (2h)**: Constructors
    - Watch: [Java Constructors by Programiz](https://www.youtube.com/watch?v=3u1rtQ0JkwE).
    - Read: [Oracle Java Tutorials - Constructors](https://docs.oracle.com/javase/tutorial/java/javaOO/constructors.html).
    - Task: Add default and parameterized constructors to `Student`. Test with different objects.
  - **Friday (2h)**: Encapsulation
    - Watch: [Encapsulation in Java by Telusko](https://www.youtube.com/watch?v=mcF2e5l3LJs).
    - Read: [GeeksforGeeks - Encapsulation](https://www.geeksforgeeks.org/encapsulation-in-java/).
    - Task: Modify `Student` to use private fields with public getters/setters. Validate id (e.g., positive). Solve 2 problems on [HackerRank Java](https://www.hackerrank.com/domains/java).

### Week 2: Inheritance
**Goal**: Master inheritance and method overriding.
- **Total Hours**: 6 hours
- **Topics**: Inheritance, super Keyword, Method Overriding
- **Learning Objectives**:
  - Create class hierarchies using inheritance.
  - Use `super` to access parent class members.
  - Override methods for customized behavior.
- **Schedule**:
  - **Monday (2h)**: Inheritance
    - Watch: [Java Inheritance by freeCodeCamp](https://www.youtube.com/watch?v=1qG2xNrfcqM) (0:30-0:50).
    - Read: [Oracle Java Tutorials - Inheritance](https://docs.oracle.com/javase/tutorial/java/IandI/inheritance.html).
    - Task: Create a `Person` parent class and `Student` child class. Test inherited fields/methods.
  - **Wednesday (2h)**: super Keyword and Method Overriding
    - Read: [GeeksforGeeks - super Keyword](https://www.geeksforgeeks.org/super-keyword/).
    - Watch: [Method Overriding by Telusko](https://www.youtube.com/watch?v=1pQ2Qh2Y9pU).
    - Task: Use `super` to call `Person` constructor in `Student`. Override a method (e.g., `introduce`) and test.
  - **Friday (2h)**: Practice
    - Task: Create a `Vehicle` hierarchy with `Car` and `Bike` subclasses. Override a `move` method. Solve 2 HackerRank problems.

### Week 3: Polymorphism and Abstract Classes
**Goal**: Understand polymorphism and abstract classes.
- **Total Hours**: 6 hours
- **Topics**: Polymorphism, Abstract Classes
- **Learning Objectives**:
  - Use polymorphism for flexible code.
  - Define and implement abstract classes.
- **Schedule**:
  - **Monday (2h)**: Polymorphism
    - Watch: [Polymorphism in Java by Telusko](https://www.youtube.com/watch?v=mKPUZ3b1Ibg).
    - Read: [Oracle Java Tutorials - Polymorphism](https://docs.oracle.com/javase/tutorial/java/IandI/polymorphism.html).
    - Task: Write a program using `Vehicle` and `Car` to demonstrate runtime polymorphism.
  - **Wednesday (2h)**: Abstract Classes
    - Watch: [Abstract Classes by freeCodeCamp](https://www.youtube.com/watch?v=1qG2xNrfcqM) (1:00-1:20).
    - Read: [GeeksforGeeks - Abstract Classes](https://www.geeksforgeeks.org/abstract-classes-in-java/).
    - Task: Create an abstract `Shape` class with an abstract `calculateArea` method. Implement in `Rectangle`.
  - **Friday (2h)**: Practice
    - Task: Create an abstract `Employee` class with `FullTimeEmployee` subclass. Implement salary calculation. Solve 2 problems on [Exercism Java Track](https://exercism.org/tracks/java).

### Week 4: Interfaces
**Goal**: Master interfaces and their applications.
- **Total Hours**: 6 hours
- **Topics**: Interfaces, Default Methods
- **Learning Objectives**:
  - Implement interfaces for multiple inheritance.
  - Use default methods in interfaces.
- **Schedule**:
  - **Monday (2h)**: Interfaces
    - Watch: [Interfaces in Java by Telusko](https://www.youtube.com/watch?v=7DcH8cDCp0o).
    - Read: [Oracle Java Tutorials - Interfaces](https://docs.oracle.com/javase/tutorial/java/IandI/interfaces.html).
    - Task: Create a `Printable` interface and implement it in `Book` class.
  - **Wednesday (2h)**: Default Methods
    - Read: [GeeksforGeeks - Default Methods](https://www.geeksforgeeks.org/default-methods-java/).
    - Task: Add a default method to `Printable` and test in a program.
  - **Friday (2h)**: Mini-Project
    - Task: Build a `Notification` system with a `Notifiable` interface and `Email`, `SMS` classes. Use default methods for logging.

### Week 5: Exception Handling
**Goal**: Learn exception handling in Java.
- **Total Hours**: 6 hours
- **Topics**: Exception Handling, Custom Exceptions
- **Learning Objectives**:
  - Handle exceptions using try-catch.
  - Create and throw custom exceptions.
- **Schedule**:
  - **Monday (2h)**: Exception Handling
    - Watch: [Exception Handling by freeCodeCamp](https://www.youtube.com/watch?v=1qG2xNrfcqM) (1:30-1:50).
    - Read: [Oracle Java Tutorials - Exceptions](https://docs.oracle.com/javase/tutorial/essential/exceptions/).
    - Task: Write a program to handle `ArithmeticException` and `NullPointerException`.
  - **Wednesday (2h)**: Custom Exceptions
    - Read: [GeeksforGeeks - Custom Exceptions](https://www.geeksforgeeks.org/user-defined-custom-exception-in-java/).
    - Task: Create a custom `InvalidAgeException` for a `Person` class. Test with try-catch.
  - **Friday (2h)**: Practice
    - Task: Refactor `Notification` project to handle exceptions (e.g., invalid email). Solve 2 HackerRank problems.

### Week 6: Packages and Design Patterns
**Goal**: Organize code with packages and learn a design pattern.
- **Total Hours**: 6 hours
- **Topics**: Packages, Singleton Pattern
- **Learning Objectives**:
  - Use packages to organize code.
  - Implement the Singleton pattern.
- **Schedule**:
  - **Monday (2h)**: Packages
    - Read: [Oracle Java Tutorials - Packages](https://docs.oracle.com/javase/tutorial/java/package/packages.html).
    - Task: Organize `Shape` hierarchy into a package (e.g., `com.example.shapes`). Test imports.
  - **Wednesday (2h)**: Singleton Pattern
    - Watch: [Singleton Pattern by Telusko](https://www.youtube.com/watch?v=QN6M5t3Ek1E).
    - Read: [GeeksforGeeks - Singleton](https://www.geeksforgeeks.org/singleton-class-java/).
    - Task: Implement a `Logger` Singleton class for logging messages.
  - **Friday (2h)**: Practice
    - Task: Refactor `Notification` project to use packages and Singleton for configuration. Solve 2 Exercism problems.

### Week 7: Collections and Mini-Project
**Goal**: Explore Java Collections and build a project.
- **Total Hours**: 6 hours
- **Topics**: Java Collections Framework
- **Learning Objectives**:
  - Use Lists and Sets for data management.
  - Apply Collections in a project.
- **Schedule**:
  - **Monday (2h)**: Java Collections
    - Watch: [Collections by Telusko](https://www.youtube.com/watch?v=MB9opWwl-iE).
    - Read: [Oracle Java Tutorials - Collections](https://docs.oracle.com/javase/tutorial/collections/).
    - Task: Write a program using `ArrayList` to store `Book` objects.
  - **Wednesday (2h)**: Mini-Project
    - Task: Build a `Library` system using `ArrayList` to manage books (add, remove, display).
  - **Friday (2h)**: Mini-Project
    - Task: Enhance `Library` to sort books by title using Collections. Solve 2 HackerRank problems.

### Week 8: Final Project and Review
**Goal**: Build a final project and consolidate knowledge.
- **Total Hours**: 6 hours
- **Topics**: Final Project (Bookstore System), Review
- **Learning Objectives**:
  - Apply all OOP concepts in a project.
  - Prepare for technical interviews.
- **Schedule**:
  - **Monday (2h)**: Project Development
    - Task: Design a `Bookstore` system with classes for `Book`, `Customer`, and `Inventory`. Use packages and Collections.
  - **Wednesday (2h)**: Project and Testing
    - Task: Implement `Inventory` management (add, sell books) with exception handling. Write basic JUnit tests.
    - Resource: [JUnit Documentation](https://junit.org/junit5/docs/current/user-guide/).
  - **Friday (2h)**: Review and Mock Interview
    - Task: Host project on GitHub with a README. Practice 3 OOP questions on [Pramp](https://www.pramp.com/). Update Notion.

## Notion Dashboard Setup
1. **Create a Table**:
   - Columns: Week, Day, Topic, Learning Objective, Tasks, Resources (with hyperlinks), Status (To Do, In Progress, Done).
   - Rows: Add entries for each study day (e.g., Week 1, Monday, Classes and Objects).
2. **Track Progress**:
   - Update Status after each session.
   - Add a Notes column for challenges or insights.
3. **Calendar View**:
   - Sync the table with a Notion calendar to visualize study days (Mon, Wed, Fri).
4. **Resources Page**:
   - Create a separate Notion page with all links below for quick access.

## Resources
- **Books**:
  - [Head First Java](https://www.oreilly.com/library/view/head-first-java/9781491910771/) by Kathy Sierra and Bert Bates – Beginner-friendly OOP concepts.
  - [Effective Java](https://www.oreilly.com/library/view/effective-java/9780134686097/) by Joshua Bloch – Advanced best practices (skim for relevant topics).
- **Online Courses**:
  - [Java OOP Tutorial by freeCodeCamp](https://www.youtube.com/watch?v=1qG2xNrfcqM) – Free, YouTube, covers core OOP.
  - [Java Programming and Software Engineering Fundamentals](https://www.coursera.org/specializations/java-programming) (Coursera, Duke University) – Paid, comprehensive.
- **Tutorials and Articles**:
  - [Oracle Java Tutorials](https://docs.oracle.com/javase/tutorial/java/) – Official documentation.
  - [GeeksforGeeks Java](https://www.geeksforgeeks.org/java/) – Topic-wise articles.
- **Practice Platforms**:
  - [HackerRank Java](https://www.hackerrank.com/domains/java) – Coding challenges.
  - [Exercism Java Track](https://exercism.org/tracks/java) – Mentored exercises.
  - [CodingBat Java](https://codingbat.com/java) – Beginner-friendly problems.
- **Interview Prep**:
  - [Pramp](https://www.pramp.com/) – Free peer-to-peer mock interviews.
  - [Cracking the Coding Interview](https://www.crackingthecodinginterview.com/) – Book for interview questions.
- **Tools**:
  - IntelliJ IDEA or Eclipse – IDE for coding.
  - GitHub – Host projects (e.g., [Bookstore](https://github.com)).
  - JUnit – For unit testing ([JUnit 5](https://junit.org/junit5/)).

## Tips for Success
- **Consistency**: Stick to the 3-day schedule to maintain momentum.
- **Active Learning**: Code every session, starting with small programs and progressing to projects.
- **Debugging**: Use IDE debugging tools to understand errors.
- **Community**: Join [r/learnjava](https://www.reddit.com/r/learnjava/) for support.
- **Portfolio**: Document the `Bookstore` project on GitHub for job applications.
- **Health**: Take short breaks within the 2-hour sessions to stay focused.