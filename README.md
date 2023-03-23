## 30 Days of Code - Day 3 - Intro to Conditional Statements

### Objective

In this challenge, we learn about conditional statements.

### Task

Given an integer, <i>n</i>, perform the following conditional actions:

<ul>
<li>If is <i>n</i> odd, print <b>Weird</b></li>
<li>If is <i>n</i> even and in the inclusive range of 2 to 5, print <b>Not Weird</b></li>
<li>If is <i>n</i> even and in the inclusive range of 6 to 20, print <b>Weird</b></li>
<li>If is <i>n</i> even and greater than 20, print <b>Not Weird</b></li>
</ul>


### Input Format

A single line containing a positive integer, <i>n</i>.

### Constraints

<ul>
<li>1 <= <i>n</i> <= 100</li>
</ul>

### Output Format

Print ```Weird``` if the number is weird; otherwise, print ```Not Weird```.

### Sample Input 0

```
3
```

### Sample Output 0

```
Weird
```

### Sample Input 1

```
24
```

### Sample Output 1

```
Not Weird
```

### Explanation

Sample Case 0: <i>n</i> = 3
<i>n</i> is odd and odd numbers are weird, so we print ```Weird```.

Sample Case 1: <i>n</i> = 24
<i>n</i> > 20 and <i>n</i> is even, so it isn't weird. Thus, we print ```Not Weird```.
