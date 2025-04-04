# GPA Calculator Program

## Overview
This is a C++ console application that calculates your semester GPA based on your inputted course names, grades, and credit hours. It uses a standard 4.0 GPA scale and handles letter grades with plus/minus variations. It’s a helpful utility for students who want a quick way to estimate their GPA.

---

##  Features
- Accepts the number of classes you are taking
- Prompts for class names, letter grades, and credit hours
- Converts letter grades (case-insensitive) to quality points
- Calculates GPA using the standard 4.0 scale
- Gracefully handles invalid or failing grades (assigns 0.0)

---

##  How to Use

### 🛠️ 1. Compile the Program
Make sure you have a C++ compiler installed. You can compile the code with:

```bash
g++ -o gpa_calculator gpa_calculator.cpp

```

### 2. Run the Program
Once compiled, run it from your terminal:

``` bash
./gpa_calculator
```
### 3. Enter Required Information
The program will ask for:

Number of classes

Names of each class

Letter grade received in each class

Credit hours for each class

Once everything is entered, your GPA will be displayed!

'''
### 4. Sample Output:
Enter the number of classes you are taking this semester: 3

Enter your class names. Hit enter after typing each class name.
Class 1: Calculus
Class 2: Physics
Class 3: Computer Science

Enter your grade for Calculus: A
Enter credit hours for Calculus: 4

Enter your grade for Physics: B+
Enter credit hours for Physics: 3

Enter your grade for Computer Science: A-
Enter credit hours for Computer Science: 3

Your GPA for this semester is: 3.73
'''
