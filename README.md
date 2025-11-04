# C++ Programming - MCQs and Coding Questions

## Part 1: Multiple Choice Questions (MCQs)

### Basic Concepts

**Q1. What is the correct syntax for a single-line comment in C++?**
- A) `<!-- comment -->`
- B) `// comment`
- C) `# comment`
- D) `/* comment */`

**Answer: B**

---

**Q2. Which symbol is used with `cout` for output?**
- A) `>>`
- B) `<<`
- C) `<>`
- D) `==`

**Answer: B**

---

**Q3. What does `endl` do in C++?**
- A) Ends the program
- B) Creates a new line
- C) Deletes a line
- D) Ends a loop

**Answer: B**

---

**Q4. Which header file is required for input/output operations?**
- A) `<cmath>`
- B) `<stdio.h>`
- C) `<iostream>`
- D) `<string>`

**Answer: C**

---

**Q5. What is the entry point of every C++ program?**
- A) `start()`
- B) `begin()`
- C) `main()`
- D) `run()`

**Answer: C**

---

### Data Types

**Q6. Which data type is used to store a single character?**
- A) `string`
- B) `char`
- C) `int`
- D) `text`

**Answer: B**

---

**Q7. What quotes are used for `char` data type?**
- A) Double quotes `" "`
- B) Single quotes `' '`
- C) Backticks `` ` ` ``
- D) No quotes

**Answer: B**

---

**Q8. Which data type stores decimal numbers with higher precision?**
- A) `int`
- B) `float`
- C) `double`
- D) `long`

**Answer: C**

---

**Q9. What value does `bool` type `true` print as?**
- A) `true`
- B) `1`
- C) `T`
- D) `yes`

**Answer: B**

---

**Q10. Which is the correct declaration of a string variable?**
- A) `string name = 'Ali';`
- B) `string name = "Ali";`
- C) `String name = "Ali";`
- D) `str name = "Ali";`

**Answer: B**

---

### Variables

**Q11. Which variable name is INVALID?**
- A) `student_age`
- B) `_count`
- C) `2ndPlace`
- D) `finalGrade`

**Answer: C** (starts with a number)

---

**Q12. What is wrong with this code: `int age 25;`**
- A) Missing semicolon
- B) Missing `=` sign
- C) Wrong data type
- D) Wrong variable name

**Answer: B**

---

**Q13. Which is a reserved word and CANNOT be used as a variable name?**
- A) `number`
- B) `count`
- C) `return`
- D) `value`

**Answer: C**

---

**Q14. What can an unsigned variable store?**
- A) Only negative values
- B) Only positive values
- C) Both positive and negative values
- D) Only zero

**Answer: B**

---

**Q15. What is the correct order for variable declaration?**
- A) `value = dataType variableName;`
- B) `dataType variableName = value;`
- C) `variableName = dataType value;`
- D) `value variableName = dataType;`

**Answer: B**

---

### Input/Output

**Q16. Which symbol is used with `cin` for input?**
- A) `<<`
- B) `>>`
- C) `==`
- D) `!=`

**Answer: B**

---

**Q17. What will this print: `cout << "age" << endl;` (assuming int age = 20)**
- A) `20`
- B) `age`
- C) `int age`
- D) Error

**Answer: B** (text in quotes prints as text)

---

**Q18. What will this print: `cout << age << endl;` (assuming int age = 20)**
- A) `age`
- B) `20`
- C) `int 20`
- D) Error

**Answer: B** (variable without quotes prints its value)

---

**Q19. Before using `cin >> name;`, what must you do?**
- A) Print the variable
- B) Declare the variable
- C) Delete the variable
- D) Nothing

**Answer: B**

---

**Q20. What prints text inside quotes as-is?**
- A) `cin`
- B) `cout`
- C) Both
- D) Neither

**Answer: B**

---

### Math Operations

**Q21. What is the result of: `10 / 2 + 3 * 2`**
- A) `10`
- B) `11`
- C) `16`
- D) `13`

**Answer: B** (10/2=5, 3*2=6, 5+6=11)

---

**Q22. What is the result of: `(2 + 3) * 4`**
- A) `14`
- B) `20`
- C) `11`
- D) `24`

**Answer: B** (2+3=5, 5*4=20)

---

**Q23. What is the order of operations in C++?**
- A) Left to right only
- B) Right to left only
- C) Parentheses, then */, then +-
- D) +-, then */, then parentheses

**Answer: C**

---

**Q24. What will print: `cout << "2 + 3" << endl;`**
- A) `5`
- B) `2 + 3`
- C) `23`
- D) Error

**Answer: B** (in quotes = text)

---

**Q25. What will print: `cout << 2 + 3 << endl;`**
- A) `2 + 3`
- B) `23`
- C) `5`
- D) Error

**Answer: C** (calculation performed)

---

### Math Library

**Q26. Which header file contains `sqrt()` and `pow()` functions?**
- A) `<iostream>`
- B) `<cmath>`
- C) `<math>`
- D) `<stdlib>`

**Answer: B**

---

**Q27. What does `sqrt(16)` return?**
- A) `2`
- B) `4`
- C) `8`
- D) `256`

**Answer: B**

---

**Q28. What does `pow(2, 3)` return?**
- A) `5`
- B) `6`
- C) `8`
- D) `9`

**Answer: C** (2^3 = 8)

---

**Q29. What does `pow(5, 2)` return?**
- A) `7`
- B) `10`
- C) `25`
- D) `52`

**Answer: C** (5^2 = 25)

---

**Q30. To use math functions, you must include:**
- A) `#include <cmath>`
- B) `#include <math.h>`
- C) Both A and B work
- D) No include needed

**Answer: C**

---

## Part 2: Coding Questions

### Easy Level

**Q1. Write a program that prints "Hello, C++" on the screen.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    cout << "Hello, C++" << endl;
    return 0;
}
```

---

**Q2. Write a program that prints your name and age.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    cout << "Name: Ahmed" << endl;
    cout << "Age: 19" << endl;
    return 0;
}
```

---

**Q3. Write a program that calculates and prints the sum of 15 and 27.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    cout << "Sum: " << 15 + 27 << endl;
    return 0;
}
```

---

**Q4. Declare an integer variable called `score` with value 95, then print it.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    int score = 95;
    cout << "Score: " << score << endl;
    return 0;
}
```

---

**Q5. Write a program that asks the user for their name and prints it back.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    string name;
    
    cout << "Enter your name: ";
    cin >> name;
    
    cout << "Hello, " << name << endl;
    
    return 0;
}
```

---

### Medium Level

**Q6. Write a program that takes two numbers from the user and prints their sum.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    int num1, num2, sum;
    
    cout << "Enter first number: ";
    cin >> num1;
    
    cout << "Enter second number: ";
    cin >> num2;
    
    sum = num1 + num2;
    
    cout << "Sum: " << sum << endl;
    
    return 0;
}
```

---

**Q7. Write a program that takes two numbers and prints their sum, difference, product, and division.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    int num1, num2;
    
    cout << "Enter first number: ";
    cin >> num1;
    
    cout << "Enter second number: ";
    cin >> num2;
    
    cout << "Sum: " << num1 + num2 << endl;
    cout << "Difference: " << num1 - num2 << endl;
    cout << "Product: " << num1 * num2 << endl;
    cout << "Division: " << num1 / num2 << endl;
    
    return 0;
}
```

---

**Q8. Write a program that asks for a student's name and three grades, then prints all the information.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    string name;
    int grade1, grade2, grade3;
    
    cout << "Enter student name: ";
    cin >> name;
    
    cout << "Enter grade 1: ";
    cin >> grade1;
    
    cout << "Enter grade 2: ";
    cin >> grade2;
    
    cout << "Enter grade 3: ";
    cin >> grade3;
    
    cout << "\nStudent Information:" << endl;
    cout << "Name: " << name << endl;
    cout << "Grade 1: " << grade1 << endl;
    cout << "Grade 2: " << grade2 << endl;
    cout << "Grade 3: " << grade3 << endl;
    
    return 0;
}
```

---

**Q9. Write a program that calculates the area of a rectangle. Ask user for length and width.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    double length, width, area;
    
    cout << "Enter length: ";
    cin >> length;
    
    cout << "Enter width: ";
    cin >> width;
    
    area = length * width;
    
    cout << "Area: " << area << endl;
    
    return 0;
}
```

---

**Q10. Write a program that converts Celsius to Fahrenheit. Formula: F = (C * 9/5) + 32**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    double celsius, fahrenheit;
    
    cout << "Enter temperature in Celsius: ";
    cin >> celsius;
    
    fahrenheit = (celsius * 9.0 / 5.0) + 32;
    
    cout << "Temperature in Fahrenheit: " << fahrenheit << endl;
    
    return 0;
}
```

---

### Advanced Level

**Q11. Write a program that calculates the square root of a number using `sqrt()` function.**

**Answer:**
```cpp
#include <iostream>
#include <cmath>
using namespace std;

int main(){
    double number, result;
    
    cout << "Enter a number: ";
    cin >> number;
    
    result = sqrt(number);
    
    cout << "Square root: " << result << endl;
    
    return 0;
}
```

---

**Q12. Write a program that calculates the area of a circle. Formula: Area = π × r². Use `pow()` for squaring. Assume π = 3.14159.**

**Answer:**
```cpp
#include <iostream>
#include <cmath>
using namespace std;

int main(){
    double radius, area;
    const double PI = 3.14159;
    
    cout << "Enter radius: ";
    cin >> radius;
    
    area = PI * pow(radius, 2);
    
    cout << "Area of circle: " << area << endl;
    
    return 0;
}
```

---

**Q13. Write a program that calculates the average of three numbers entered by the user.**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    double num1, num2, num3, average;
    
    cout << "Enter first number: ";
    cin >> num1;
    
    cout << "Enter second number: ";
    cin >> num2;
    
    cout << "Enter third number: ";
    cin >> num3;
    
    average = (num1 + num2 + num3) / 3;
    
    cout << "Average: " << average << endl;
    
    return 0;
}
```

---

**Q14. Write a program that calculates compound interest. Formula: A = P(1 + r)^t. Use `pow()` function.**

**Answer:**
```cpp
#include <iostream>
#include <cmath>
using namespace std;

int main(){
    double principal, rate, time, amount;
    
    cout << "Enter principal amount: ";
    cin >> principal;
    
    cout << "Enter rate of interest: ";
    cin >> rate;
    
    cout << "Enter time (years): ";
    cin >> time;
    
    amount = principal * pow((1 + rate), time);
    
    cout << "Total amount: " << amount << endl;
    
    return 0;
}
```

---

**Q15. Write a program that takes base and height of a triangle and calculates its area. Formula: Area = (base × height) / 2**

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    double base, height, area;
    
    cout << "Enter base of triangle: ";
    cin >> base;
    
    cout << "Enter height of triangle: ";
    cin >> height;
    
    area = (base * height) / 2;
    
    cout << "Area of triangle: " << area << endl;
    
    return 0;
}
```

---

## Part 3: Error Finding Questions

**Q16. Find and fix the errors:**
```cpp
#include <iostream>
using namespace std;

int main(){
    int age
    cout << Enter your age: ;
    cin << age;
    cout << "Your age is " age << endl;
    return 0;
}
```

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    int age;  // Missing semicolon
    cout << "Enter your age: ";  // Missing quotes
    cin >> age;  // Wrong operator (should be >>)
    cout << "Your age is " << age << endl;  // Missing 
    return 0;
}
```

---

**Q17. Find and fix the errors:**
```cpp
#include <iostream>
using namespace std;

int main(){
    string name = Ahmed;
    char grade = "A";
    cout << name << end;
    return 0;
}
```

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    string name = "Ahmed";  // String needs quotes
    char grade = 'A';  // Char uses single quotes
    cout << name << endl;  // Should be endl not end
    return 0;
}
```

---

**Q18. Find and fix the errors:**
```cpp
#include <iostream>
using namespace std;

int main(){
    int 1stNumber = 10;
    cout << The number is << 1stNumber << endl;
    return 0;
}
```

**Answer:**
```cpp
#include <iostream>
using namespace std;

int main(){
    int firstNumber = 10;  // Variable can't start with number
    cout << "The number is " << firstNumber << endl;  // Missing quotes
    return 0;
}
```

---

## Part 4: Output Prediction Questions

**Q19. What will this program print?**
```cpp
#include <iostream>
using namespace std;

int main(){
    int x = 5;
    int y = 3;
    cout << x + y * 2 << endl;
    return 0;
}
```

**Answer:** `11` (because 3*2=6, then 5+6=11)

---

**Q20. What will this program print?**
```cpp
#include <iostream>
using namespace std;

int main(){
    cout << "Result: " << (10 - 4) / 2 << endl;
    return 0;
}
```

**Answer:** `Result: 3` (because 10-4=6, then 6/2=3)

---
