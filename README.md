# Bitwise NOT Operator in Java
This simple Java program demonstrates the use of the **bitwise NOT (~)** operator.

## 🧠 What is Bitwise NOT?

The bitwise NOT operator (`~`) in Java inverts each bit of the integer:
- It changes every `0` to `1` and every `1` to `0`.
- It effectively computes the **two's complement** of the number and subtracts 1.
- So `~x` is equivalent to `-x - 1`.

## 📌 Program Overview

```java
class Bitwise2 {
    public static void main(String[] args) {
        int a = 65;
        int b = ~a;
        System.out.println("~a = " + b);
    }
}
