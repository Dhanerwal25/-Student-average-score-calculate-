# Student Score & Grade Calculator 🎓

A C# console application that calculates the total sum and decimal average scores for students across multiple graded assignments, and displays their final grades in a formatted console report.

## ✨ Features

- **Score Summation:** Computes the total points earned by each student across 5 graded assignments.
- **Decimal Average Calculation:** Converts integer scores into decimal averages for accurate grading.
- **Formatted Output:** Uses C# string interpolation and tab escape sequences (`\t`) to display a clean summary of student names, average scores, and letter grades.

## 🛠️ Built With

- **Language:** C#
- **Framework:** .NET SDK

## 📊 Student Data & Calculations

The application processes scores for 4 students across **5 assignments**:

| Student | Assignment Scores | Total Sum | Average Score | Grade |
| :--- | :--- | :---: | :---: | :---: |
| **Sophia** | 93, 87, 98, 95, 100 | 473 | 94.6 | A |
| **Nicolas** | 80, 83, 82, 88, 85 | 418 | 83.6 | B |
| **Zahirah** | 84, 96, 73, 85, 79 | 417 | 83.4 | B |
| **Jeong** | 90, 92, 98, 100, 97 | 477 | 95.4 | A |

## 📋 Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (Version 6.0, 8.0, or higher)
- Visual Studio or Visual Studio Code

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   
   git clone https://github.com/Dhanerwal25/-Student-average-score-calculate-/tree/main
   ```

2. **Navigate to the project directory**
   ```bash
   cd student-score-calculator
   ```

3. **Run the application**
   ```bash
   dotnet run
   ```

## 💻 Expected Output

```text
473
418
417
477
Student		Grade	Credit
Sophia:		94.6	A
Nicolas:	83.6	B
Zahirah:	83.4	B
Jeong:		95.4	A
```

## 🧠 Concepts Practiced

- Declaring and initializing `int` and `decimal` variables
- Performing arithmetic operations (`+`, `/`)
- Explicit type casting (`(decimal)`)
- Formatting console output with string interpolation (`$""`) and escape characters (`\t`)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
