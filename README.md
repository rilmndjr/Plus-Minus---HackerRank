# PlusMinus Function

Given an array of integers, calculate the ratios of its elements that are positive, negative, and zero. Print the decimal value of each fraction on a new line with 6 places after the decimal.

**Note**: This challenge introduces precision problems. The test cases are scaled to six decimal places, though answers with absolute error of up to \(10^{-4}\) are acceptable.

## Example

There are 5 elements, two positive, two negative, and one zero. Their ratios are 2/5, 2/5, and 1/5. Results are printed as:
0.400000
0.400000
0.200000


## Function Description

Complete the `plusMinus` function in the editor below.

### plusMinus

#### Parameters:
- `int arr[n]`: an array of integers

#### Print:
Print the ratios of positive, negative, and zero values in the array. Each value should be printed on a separate line with 6 digits after the decimal. The function should not return a value.

## Input Format

The first line contains an integer, `n`, the size of the array.  
The second line contains `n` space-separated integers that describe `arr`.

## Constraints

- \(0 < n \leq 100\)
- \(-100 \leq arr[i] \leq 100\)

## Output Format

Print the following 3 lines, each to 6 decimals:

1. Proportion of positive values
2. Proportion of negative values
3. Proportion of zeros

