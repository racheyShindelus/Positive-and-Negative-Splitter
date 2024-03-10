# Positive and Negative Splitter

This C program splits an array into two separate arrays: one containing positive numbers and the other containing negative numbers.

## How it Works

1. The program defines an array `source` of a constant size and either fills it with random values or constant values based on the value of the `RAND_ARR` constant.
2. It then initializes two arrays `pos` and `neg` to store positive and negative numbers respectively.
3. It iterates through the `source` array and adds positive numbers to the `pos` array and negative numbers to the `neg` array, maintaining separate lengths for both arrays.
4. Finally, it prints the contents of both the `pos` and `neg` arrays.

## Instructions

1. **Compile**: Compile the program using a C compiler. For example, using GCC:
    ```bash
    gcc positive_negative_splitter.c -o positive_negative_splitter
    ```

2. **Execute**: Run the compiled program:
    ```bash
    ./positive_negative_splitter
    ```

## Example

pos: 9 2 0 0 21 1 10 2

neg: -4 -92


## Notes

- The program can be configured to fill the `source` array with random values by changing the value of the `RAND_ARR` constant.
- It demonstrates array manipulation and conditional statements.
