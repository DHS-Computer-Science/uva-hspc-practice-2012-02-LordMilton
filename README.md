# Practice 2012 - 02: Reducing Improper Fractions

## Background
You were invited to a St. Patrick’s Day party, but you aren’t allowed to
leave until you finish your fraction reduction homework. You want to go
to the party as soon as possible so you decide to write a program to do
your homework for you. Given an improper fraction, calculate its reduced
form.

## Description

### Input
The first line of input is the number of test cases that follow. Each test
case is a line containing two integer values. The first integer value will be
the numerator n (0 ≤ n ≤ 10 9 ), the second integer is the denominator d
(0 < d ≤ 10 9 ).

### Output
For each case output the line “Case x:” where x is the case number, on a single
line, followed by a space, and then proper fraction. Each fraction will be of
the form “I N/D”, where I is the integer part, N is the numerator of the
fractional part, and D is the denominator of the fractional part. If the integer
value is less than than 0, only output “N/D”. If both the integer value and the
reduced numerator are zero, output “0”. If there is no fractional part,
only output “I”.

## Sample
### Input
```
4
301 100
89 39
50 25
25 50
```

### Output
```
Case 1: 3 1/100
Case 2: 2 11/39
Case 3: 2
Case 4: 25/50
```
