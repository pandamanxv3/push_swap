# Push_swap Project README

## Introduction
Push_swap is a C programming project that focuses on data sorting through algorithmic efficiency and optimization. It challenges students to develop a program that sorts integers using the least number of operations possible. The project uses two stacks and a set of operations to manipulate these stacks. It's an excellent opportunity for budding programmers to engage with algorithmic complexity and sorting algorithms, a staple in computer science education and technical interviews.

## Project Overview
- **Language**: Entirely written in C.
- **Objective**: To create a program named `push_swap` that sorts integers using the least number of operations.
- **Components**:
  - **Two Stacks**: Named 'a' and 'b', where stack 'a' contains a random set of integers and stack 'b' is initially empty.
  - **Set of Instructions**: Specific commands to manipulate stacks, such as `sa` (swap a), `pb` (push b), `ra` (rotate a), etc.

## Algorithm Used
- **Longest Increasing Subsequence (LIS)**: This algorithm is employed to identify a subsequence of a given sequence in which the elements are in sorted order. LIS is crucial in reducing the number of operations needed to sort the entire stack. It helps in strategically moving elements between stacks to minimize sorting operations.

## Key Features
- **Efficient Sorting**: The program must sort the integers in stack 'a' in ascending order with minimal operations.
- **Error Handling**: Properly handles errors like invalid input, duplicates, or overflow.
- **Optimized Algorithm**: Utilizes the Longest Increasing Subsequence algorithm to enhance sorting efficiency.

## Project Constraints
- **Written in C**: Adheres strictly to the C programming language for all functionalities.
- **No Global Variables**: Ensures encapsulation and modular programming.
- **Norm Compliance**: Code must adhere to specific coding standards set by the school.
- **Memory Management**: Efficient use of memory with no leaks tolerated.
- **Makefile**: Includes a Makefile with rules: NAME, all, clean, fclean, re.
- **Error Messages**: Displays "Error" followed by a newline for any input or execution errors.

## Usage
- To run the program, integers to be sorted are passed as arguments to `push_swap`.
- The output is a series of operations that sort the stack, each operation separated by a newline.
- Example usage:
  ```bash
  ./push_swap 2 1 3 6 5 8
  ```
