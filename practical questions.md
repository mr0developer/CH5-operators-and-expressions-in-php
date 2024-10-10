### 1. Program to Calculate Total Number of Days Lived

```php
<?php
// Input age
$age = 25; // Example: Enter your age here
$number_of_days = $age * 365;

// Output
echo "You have lived for $number_of_days days.";
?>
```

This program multiplies the age in years by 365 to calculate the total number of days lived.

---

### 2. Program to Calculate Percentage of a Student

```php
<?php
// Input marks for four subjects
$subject1 = 85; // Example marks for subject 1
$subject2 = 90; // Example marks for subject 2
$subject3 = 88; // Example marks for subject 3
$subject4 = 92; // Example marks for subject 4

// Calculations
$obtained_marks = $subject1 + $subject2 + $subject3 + $subject4;
$total_marks = 400;
$percentage = ($obtained_marks * 100) / $total_marks;

// Output
echo "Obtained Marks: $obtained_marks out of $total_marks <br>";
echo "Percentage: $percentage%";
?>
```

This program calculates the student's percentage based on the marks in 4 subjects.

---

### 3. Program to Convert Temperature from Centigrade to Fahrenheit

```php
<?php
// Input temperature in Centigrade
$centigrade = 25; // Example temperature
$fahrenheit = ($centigrade * 9/5) + 32;

// Output
echo "$centigrade°C is equal to $fahrenheit°F";
?>
```

This program converts temperature from Centigrade to Fahrenheit using the formula `F = (C * 9/5) + 32`.

---

### 4. Logical Operations on Given Values

Given: `$A = 34` and `$B = 55`.

```php
<?php
$A = 34;
$B = 55;

// Logical expressions
echo "a) " . ($A == 34 && $B == 55 ? 'true' : 'false') . "<br>";
echo "b) " . ($A >= 30 || $B <= 50 ? 'true' : 'false') . "<br>";
echo "c) " . ($B == 55 || $A == 35 ? 'true' : 'false') . "<br>";
echo "d) " . ($A != 34 ? 'true' : 'false') . "<br>";
echo "e) " . ($A >= 30 && $A < 35 ? 'true' : 'false') . "<br>";
echo "f) " . ($B > 50 || $B < 56 ? 'true' : 'false') . "<br>";
?>
```

**Explanation of Results:**
- a) `true` because both conditions (`$A == 34` and `$B == 55`) are true.
- b) `true` because `$A >= 30` is true (even though `$B <= 50` is false).
- c) `true` because `$B == 55` is true (even though `$A == 35` is false).
- d) `false` because `$A != 34` is false (since `$A` is equal to 34).
- e) `true` because both conditions (`$A >= 30` and `$A < 35`) are true.
- f) `true` because `$B > 50` is true.

---

### 5. Output of the Following Code

```php
<?php
$a = 33;
$b = 55;
$a += $b; // $a becomes 88
$c = $a;  // $c is now 88
$c -= $b; // $c becomes 33
$c *= $a; // $c becomes 2904
$a++;     // $a becomes 89

echo "a=$a, b=$b, c=$c";
?>
```

**Output**:
```
a=89, b=55, c=2904
```

---

### 6. Output of the Program Segment

```php
<?php
$a = 8;
$b = ++$a + 5; // Pre-increment: $a becomes 9, then $b = 9 + 5 = 14
$c = $b-- + 10; // Post-decrement: $c = 14 + 10 = 24, then $b becomes 13

echo "a=$a, b=$b, c=$c";
?>
```

**Output**:
```
a=9, b=13, c=24
```

---

### 7. Output of the Arithmetic Expressions

a) `echo 4 + 2 - 12 * 3;`

**Output**: `-30`

**Explanation**: Multiplication is done first, so:
`12 * 3 = 36`, then `4 + 2 = 6`, and `6 - 36 = -30`.

---

b) `echo 4 + (2 - 12) * 3;`

**Output**: `-26`

**Explanation**: The operation inside parentheses is done first:
`2 - 12 = -10`, then `-10 * 3 = -30`, and `4 + (-30) = -26`.

---

c) `echo ( (4 + 2) - 12 ) * 3;`

**Output**: `-18`

**Explanation**: The operation inside parentheses is done first:
`(4 + 2) = 6`, then `6 - 12 = -6`, and `-6 * 3 = -18`.

---

### 8. Value Assigned to `$ReturnValue`

a) `$ReturnValue = 2 == 3;`

**Value**: `false`

**Explanation**: `2` is not equal to `3`.

---

b) `$ReturnValue = "2" + "3";`

**Value**: `5`

**Explanation**: Strings are automatically converted to numbers, so `"2"` + `"3"` becomes `2 + 3 = 5`.

---

c) `$ReturnValue = 2 > 3;`

**Value**: `false`

**Explanation**: `2` is not greater than `3`.

---

d) `$ReturnValue = 2 < 3;`

**Value**: `true`

**Explanation**: `2` is less than `3`.

---

e) `$ReturnValue = (2 > 3) && (2 < 3);`

**Value**: `false`

**Explanation**: The first condition `2 > 3` is false, and with the `&&` operator, both conditions must be true.

---

f) `$ReturnValue = (2 > 3) || (2 < 3);`

**Value**: `true`

**Explanation**: The second condition `2 < 3` is true, and with the `||` operator, only one condition needs to be true for the whole expression to be true.
