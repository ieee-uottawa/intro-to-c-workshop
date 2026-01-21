# Intro to C Workshop – Practice Questions

Link to presentation: [Intro to C Workshop – Presentation](https://docs.google.com/presentation/d/1vNBTdgKRKvzyWMiPT5RDtsl_q4GC_yjCOyyML4J4AgE/edit?usp=sharing)

Complete each of the following questions in C.

---

## Question 1 – Hello World

Create a program which prints:

```txt
Hello World!
```

---

## Question 2 – User Input (Integer)

Create a program which:

1. Asks the user to input an integer.
2. Prints the integer back to the screen.

---

## Question 3 – Area of a Circle

Create a program which:

1. Defines a float `p` as the value of π (PI) to **3 decimal places**.
2. Asks the user to input a radius.
3. Calculates the area of the circle.
4. Prints the result to **3 decimal places**.

Formula for the area of a circle:

```txt
Area = p * r²
```

---

## Question 4 – Countdown with Loops and Arrays

Create a program which:

1. Prints the word `countdown`.
2. Prints a countdown from **5 to 1**.
3. Uses **loops and arrays**.

Example output:

```txt
countdown
5
4
3
2
1
```

---

## Question 5 – Printing Your Name

Create a program which prints your name using:

* **Loops**
* **Strings**

---

## Question 6 – Pointers Only

Create a program which prints the integer:

```txt
10
```

You must use **only pointers and addresses** to accomplish this.

(No direct printing of the number is allowed.)

---

## Question 7 – Functions and Pointers

Create a program which:

1. Starts with a value of `20`.
2. Uses a `void` function named `divide_by_10`.
3. Divides the value by 10 using **pointers and addresses**.
4. Prints the value **before** and **after** the division.

Function prototype:

```c
void divide_by_10(float *value);
```

---

## Question 8 – Structures

Create a structure that allows tracking employees in a company with:

* Name
* Employee ID
* Department
* Salary

Then print each employee’s:

* Employee ID
* Department
* Salary

Use the following employees:

| Name  | ID    | Department | Salary |
| ----- | ----- | ---------- | ------ |
| Bob   | 30894 | HR         | 83000  |
| Megan | 29836 | Marketing  | 85900  |
| Steph | 98763 | IT         | 92500  |
| Mo    | 93087 | IT         | 93840  |

---

## Question 9 – Dynamic Memory Allocation (malloc and free)

Create a program which:

1. Asks the user how many integers they want to store.
2. Dynamically allocates enough memory to store that many integers using `malloc`.
3. Uses a loop to let the user input each integer.
4. Prints all the integers back to the screen.
5. Frees the allocated memory using `free`.

Rules:

* You must use `malloc` to allocate the array.
* You must check that `malloc` was successful.
* You must use `free` before the program exits.

Example run:

```txt
How many numbers do you want to store? 4
Enter number 1: 10
Enter number 2: 25
Enter number 3: 7
Enter number 4: 42

You entered:
10
25
7
42
```
