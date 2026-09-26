# Day-109-Reverse-List
# Python Day 109 - Reverse a List

This program reverses a list using list slicing `[::-1]`.

## Example

Original list:

```text id="original109"
[10, 20, 30, 40, 50]
```

Reversed list:

```text id="reverse109"
[50, 40, 30, 20, 10]
```

## Concepts Used

* List
* List slicing
* `[::-1]`
* Variables
* Reverse order

## How It Works

1. A list of numbers is created.
2. The original list is displayed.
3. `[::-1]` is used to create a reversed version of the list.
4. The reversed list is stored in `reversed_numbers`.
5. The reversed list is displayed.

## Python Code

```python id="code109"
numbers = [10, 20, 30, 40, 50]

print("Original list:", numbers)

reversed_numbers = numbers[::-1]

print("Reversed list:", reversed_numbers)
```

## Output

```text id="output109"
Original list: [10, 20, 30, 40, 50]
Reversed list: [50, 40, 30, 20, 10]
```

## Goal

The goal of this project is to understand list slicing and learn how to reverse a list using `[::-1]` in Python.
