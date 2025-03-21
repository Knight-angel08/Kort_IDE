Kort Language Documentation

1. Introduction

Kort is an intuitive, beginner-friendly programming language designed to allow users to write simple yet powerful applications across different devices, from desktops to custom smartphones and IoT devices. It is optimized for ease of use, automatic type inference, and flexible device compatibility.

Kort's unique approach allows users to focus on writing code without worrying about low-level programming concerns. Kort is a transpiler-based language, which means it automatically converts your code to the most appropriate target language (such as Python, C, or other low-level languages) depending on the system it is running on.


---

2. Kort Language Series

Kort is divided into several versions, each designed to cater to different levels of programming expertise:

2.1 Kort (Basic Version)

Target Audience: Beginners, hobbyists, and educational users

Purpose: Simple application development, IoT, basic automation, device control, etc.

Features:

Python-like syntax: Simple, easy-to-understand syntax for rapid development.

Dynamic Typing: No need to declare variable types. Types are inferred automatically.

Basic Functionality: Designed for simple tasks such as creating 2D games, calculators, automation scripts, etc.

No OOP: Initially procedural, with support for basic functions, loops, and conditionals.

Transpiler-based: Automatically converts code into Python or C, depending on the platform.



Example:

x = 5  # integer assignment
y = 3.14  # real number
name = 'John'  # string assignment
prt['Hello, World!']  # Output

2.2 Kort_X (Most Advanced Version)

Target Audience: Experienced developers, system programmers, AI researchers

Purpose: Full-fledged application development, OS creation, AI programming, advanced IoT systems.

Features:

All-in-One Solution: Capable of developing operating systems, AI systems, complex embedded systems, and device control programs.

AI-Powered Suggestions: Provides real-time code suggestions, fixes, and refactoring through an integrated AI assistant.

Multilingual Support: Supports multiple programming paradigms (procedural, object-oriented, functional, etc.).

Full Hardware Support: Can interact with hardware at the chip level, useful for IoT development.

AI-Assisted IDE: Features autocomplete, intelligent error corrections, and optimizations.



Example:

# Creating a Neural Network Example in Kort_X
from kort_x import nn
network = nn.create_neural_network([5, 10, 3])  # Creates a network with 5 input neurons, 10 hidden, 3 output
network.train(training_data)

2.3 Kort+<version> (Intermediate Versions)

Target Audience: Intermediate developers

Purpose: Suitable for users who are comfortable with programming but don’t need the full complexity of Kort_X.

Features:

Provides an enhanced set of features compared to Kort.

Adds better abstractions for working with libraries, modules, and file handling.

Supports some advanced functions for system programming, but not to the level of Kort_X.



2.4 Kort_edge and Kort_surface

Target Audience: Specialized use-cases, such as embedded systems or custom hardware development.

Purpose: Optimized for specific tasks like device control, hardware programming, sensor interfacing, etc.

Features:

Edge Computing: For real-time, low-latency device control and computation.

Surface Programming: Optimized for touch interfaces and custom devices.

Limited Scope: Not as full-featured as Kort or Kort_X, but designed for highly specific applications.




---

3. Language Features

3.1 Data Types

Kort supports a variety of built-in data types. Each data type serves different purposes, and you can choose the most appropriate one based on your requirements.

Data Types Supported in Kort:

Integer (Z): Whole numbers, both positive and negative (e.g., 5, -2).

Real (R): Real numbers (e.g., 3.14, -2.71).

Rational (Q): Rational numbers (fractions) such as 1/2 or 3/4.

Irrational (IR): Numbers like pi (π), Euler's number (e), square roots, etc. (e.g., π, √2).

Complex (C): Numbers in the form a + bi (e.g., 3 + 4i).

Whole (W): Whole numbers, which are non-negative integers (e.g., 0, 1, 2).

Natural (N): Natural numbers, positive integers starting from 1 (e.g., 1, 2, 3).


Example Usage:

# Integer
x = Z(5)  
# Rational Number
y = Q(1, 2)  # Represents 1/2
# Irrational Number
z = IR(π)  # Represents the value of pi
# Complex Number
a = C(3, 4)  # Represents 3 + 4i

3.2 Functions

Functions are defined using the def keyword in Kort, and function calls are made using the same syntax as in Python.

def add(a, b):
    return a + b

result = add(3, 4)  # result will be 7

3.3 Loops & Conditionals

Kort supports common control flow structures like for loops, while loops, and if statements.

For Loop Example:

for i in range(1, 10):
    prt[i]

While Loop Example:

i = 0
while i < 10:
    prt[i]
    i += 1

Conditional Example:

x = 5
if x > 0:
    prt["Positive"]
elif x == 0:
    prt["Zero"]
else:
    prt["Negative"]

3.4 Mathematical Operations

Kort supports a wide range of mathematical operations, including:

Addition, subtraction, multiplication, division

Exponential and logarithmic operations

Trigonometric functions

Integration and differentiation


Example of Basic Math Operations:

a = 10
b = 5
sum_result = a + b
product_result = a * b


---

4. Libraries and Modules

Kort comes with built-in libraries that provide powerful tools for users to perform advanced tasks easily.

4.1 Maths Library

This library includes:

Limits and Continuity: Functions for calculating the limits of mathematical expressions.

Integration & Differentiation: Both definite and indefinite integrals, derivatives, etc.

Expansions: Expansions for functions like log(1 + x), e^x, and sin(x).


Example:

from maths import limits, integration

result_limit = limits.calculate_limit(f(x), x, 0)  # Calculate the limit of f(x) as x approaches 0
result_integration = integration.definite_integral(f(x), 0, 1)  # Integral of f(x) from 0 to 1

4.2 Physics Library (phys)

This library includes various functions to calculate important physical quantities across different branches of physics like mechanics, thermodynamics, electromagnetism, and optics.

Example Usage:

from phys import mechanics, thermodynamics

velocity = mechanics.calculate_velocity(distance, time)
pressure = thermodynamics.calculate_pressure(force, area)

4.3 File Handling

Kort allows users to handle files efficiently, supporting various file types such as .txt, .csv, .py, .html, and .env.

Example:

file.new["/path/to/directory", "file_name", ".txt"]  # Create a new text file


---

5. Error Handling

Kort provides meaningful error messages to help users understand and resolve issues with their code. It also provides suggestions to fix common errors.

Example of Error Message:

// *error: File not found


---

6. Conclusion

Kort is a powerful yet simple language that supports both beginners and advanced programmers. Its unique transpiling capabilities, combined with powerful libraries for mathematics, physics, and more, make it ideal for a wide range of applications, from simple automation scripts to complex system development.
