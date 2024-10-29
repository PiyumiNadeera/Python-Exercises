# Python Programming Exercises

This repository contains 10 Python programming exercises designed to practice object-oriented programming concepts, file handling, and data structures. Each exercise focuses on building a small system that performs specific tasks and saves data in different formats like text, JSON, and CSV.

## Table of Contents
1. [Library Management System](Exercise_1.ipynb)
2. [Student Grades System](Exercise_2.ipynb)
3. [Task Manager](Exercise_3.ipynb)
4. [Shopping Cart](Exercise_4.ipynb)
5. [Movie Database](Exercise_5.ipynb)
6. [Phonebook](Exercise_6.ipynb)
7. [Stack Implementation](Exercise_7.ipynb)
8. [Queue Implementation](Exercise_8.ipynb)
9. [Recipe Book](Exercise_9.ipynb)
10. [Weather Data Analyzer](Exercise_10.ipynb)

---

## Exercise 1: Library Management System
**Description:**  
- Implements a `Book` class with attributes: `title`, `author`, and `isbn`.
- The `Library` class manages a collection of books, providing methods to:
  - Add a book.
  - Remove a book.
  - Search for books by title or author.
- Stores book details in a text file for persistence.

---

## Exercise 2: Student Grades System
**Description:**  
- Implements a `Student` class with attributes: `name`, `id`, and a list of `grades`.
- Provides methods to:
  - Add grades.
  - Calculate the average grade.
  - Determine if the student passed (average >= 60).
- Stores student details in a JSON file for persistence.

---

## Exercise 3: Task Manager
**Description:**  
- Implements a `Task` class with attributes: `title`, `description`, and `status`.
- The `TaskManager` class manages tasks using a queue. Provides methods to:
  - Add a task.
  - Complete a task.
  - Display pending tasks.
- Saves task list to a CSV file for persistence.

---

## Exercise 4: Shopping Cart
**Description:**  
- Implements a `Product` class with attributes: `name`, `price`, and `quantity`.
- The `ShoppingCart` class allows users to:
  - Add and remove products.
  - Calculate the total price of items in the cart.
- Stores cart contents in a dictionary for easy access.

---

## Exercise 5: Movie Database
**Description:**  
- Implements a `Movie` class with attributes: `title`, `genre`, and `rating`.
- The `MovieDatabase` class allows users to:
  - Add movies.
  - Search for movies by genre.
  - Display all movies sorted by rating.
- Uses a set to store unique genres.

---

## Exercise 6: Phonebook
**Description:**  
- Implements a `Contact` class with attributes: `name`, `phone`, and `email`.
- The `Phonebook` class allows users to:
  - Add, remove, and search for contacts.
- Stores contacts in a dictionary and saves/loads the phonebook from a text file for persistence.

---

## Exercise 7: Stack Implementation
**Description:**  
- Implements a `Stack` class with methods to:
  - Push an item onto the stack.
  - Pop an item off the stack.
  - Check if the stack is empty.
- Provides a function to check if a string of parentheses is balanced using the `Stack` class.

---

## Exercise 8: Queue Implementation
**Description:**  
- Implements a `Queue` class with methods to:
  - Enqueue an item.
  - Dequeue an item.
  - Check if the queue is empty.
- Provides a function to simulate a ticketing system where customers join a queue and are served in order.

---

## Exercise 9: Recipe Book
**Description:**  
- Implements a `Recipe` class with attributes: `name`, `ingredients`, and `instructions`.
- The `RecipeBook` class allows users to:
  - Add, remove, and search for recipes.
- Stores recipes in a JSON file for persistence.

---

## Exercise 10: Weather Data Analyzer
**Description:**  
- Implements a `WeatherData` class to store temperature data for a week.
- Provides methods to:
  - Calculate the average temperature.
  - Find the highest and lowest temperatures.
- Stores data in a tuple and reads/writes data from/to a CSV file.

---

## Getting Started

### Prerequisites
To run these exercises, you need Python installed on your machine. You can download it from the [official Python website](https://www.python.org/downloads/).

### Running the Exercises
Each exercise is contained in its own Python file (e.g., `exercise_1.py`, `exercise_2.py`, etc.). You can run them individually by executing:

```bash
python exercise_1.py
```

Replace `exercise_1.py` with the respective filename for each exercise.

### File Formats Used
- **Text Files:** Used to store book and phonebook details.
- **JSON Files:** Used to store student grades and recipes.
- **CSV Files:** Used to store task lists and weather data.

---

## Contributing
If you'd like to contribute or improve any exercise, feel free to submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

