# Advent of Code: Day 1

Santa is trying to deliver presents in a large apartment building, but he can't find the right floor due to confusing directions. The instructions consist of opening and closing parentheses, where an opening parenthesis "(" means going up one floor, and a closing parenthesis ")" means going down one floor. The goal is to determine the floor Santa ends up on.

## Part 1

### Problem Description

Given a string of parentheses instructions, calculate the floor Santa ends up on.

### Example

For the input:

```php
(()) and ()()

```

The output should be 0.

## Part 2

### Problem Description

Now, find the position of the first character that causes Santa to enter the basement (floor -1). The positions are 1-indexed.

### Example

For the input:

```php
) causes him to enter the basement at character position 1.
()()) causes him to enter the basement at character position 5.

```

The output should be the position where Santa first enters the basement.
