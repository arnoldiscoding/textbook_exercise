# Review Exercise

## R2.1

a. The number of days per wek should be an **integer**, as it is impossible to have a floating-point number of days in a week (e.g. 6.5 days a week)

b. The number of days until the end of the semester should be an **integer**, as it is impossible to have a floating-point number of days.

c. The number of centimetres in an inch should be a **floating-point number**, as there is 2.54 centimetres in an inch, which could only be stored by floating points.

d. The height of the tallest person in a class should be a **floating-point number**, as height may not be an exact whole number.

## R2.2

The value of mystery will be 0.

1. mystery is initialised to be 1
2. mystery is multiplied by 2, which is equal to 2, then 1 is subtracted by the result, making the result -1. -1 is then assigned back to mystery.
3. We add 1 to mystery, making it 0 and assign it back to mystery.

## R2.3

The value of mystery will be -3.

1. mystery is initialised to be 1
2. We add 1 to mystery, making it 2 and assign it back to mystery.
3. We first multiply mystery by 2, making it 4, then using it to subtract 1, making -3. Finally we assign -3 back to mystery.

## R2.4

a.

```cpp
s = s0 + v0 * t + 0.5 * g * t * t
```

b.

```cpp
#include <cmath> // Remember to include the cmath library or else you cannot use the power function
FV = PV * pow(1 + INT / 100, YRS)
```

b.

```cpp
#include <cmath> // Remember to include the cmath library or else you cannot use the power function
FV = PV * pow(1 + INT / 100, YRS)
```

c.

```cpp
#include <cmath> // Remember to include the cmath library or else you cannot use the power function and the M_PI constant
G = 4 * pow(M_PI,2) * pow(a, 3) / (pow(p, 2) * (m1 + m2))
```

d.

```cpp
#include <cmath> // Remember to include the cmath library or else you cannot use the sqrt, pow function
c = sqrt(pow(a, 2) + pow(a, 2) - 2 * a * b * cos(gamma))
```

## R2.5

a.

$$
dm = m (\frac{\sqrt{\frac{1+v}{c}}}{\sqrt{\frac{1-v}{c}}} - 1)
$$

b.

$$
volume = \pi r^2 h
$$

c.

$$
volume = 4 * \pi \frac{r^3}{3}
$$

d.

$$
z = \sqrt{x^2y^2}
$$
