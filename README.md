# Fibonacci
Fibonacci generator

---

## 📌 Features

* Accepts user input for how many Fibonacci terms to generate.
* Prints the Fibonacci sequence starting from 0.
* Simple, beginner-friendly logic using iterative calculation.


## 📂 Project Structure

```
day6/
└── Fibonacci.java
```

---

## 🧑‍💻 How It Works

1. The program asks the user:
   **"Enter the number of terms in a Fibonacci series:"**
2. It initializes the first two terms (`a = 0`, `b = 1`).
3. It iteratively calculates and prints Fibonacci numbers up to the number of terms the user requested.

---

## ▶️ How to Run

1. Ensure you have **Java installed** (JDK 8 or above).

2. Save the file as `Fibonacci.java` inside a folder named `day6`.

3. Compile the program:

   ```bash
   javac day6/Fibonacci.java
   ```

4. Run it:

   ```bash
   java day6.Fibonacci
   ```

5. Enter a number when prompted.

---

## 📝 Example Output

```
Enter the number of terms in a Fibonacci series:
5
Fibonacci Sequence:
0
1
1
2
3
```

---

## 📘 Code Reference

```java
package day6;

import java.util.Scanner;

public class Fibonacci {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter the number of terms in a Fibonacci series:");
        int terms = scanner.nextInt();
        int a = 0, b = 1;

        System.out.println("Fibonacci Sequence:");
        for (int i = 1; i <= terms; i++) {
            System.out.println(a + "");
            int next = a + b;
            a = b;
            b = next;
        }
    }
}



✅ Rewrite for a classroom assignment
Just let me know!
