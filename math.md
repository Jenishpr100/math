# What Integrals Are

- Integrals are a part of calculus used to find the **accumulation** of quantities.
- They are often used to calculate **area under a curve**, **total distance traveled**, **volume**, and other changing quantities.
- An integral can be thought of as the **opposite of a derivative**.

## Types of Integrals

### 1. Indefinite Integrals
- An indefinite integral finds the **general antiderivative** of a function.
- It does not have boundaries.
- The answer includes **+ C**, called the constant of integration.

Example:


# $\int x^2 dx = \frac{x^3}{3} + C$


### 2. Definite Integrals
- A definite integral finds the **exact accumulated value** between two points.
- It has **upper and lower limits**.
- Often used to find the **area under a graph**.

Example:


# $\int_{0}^{2} x^2 dx$


## Integral Symbol

The integral symbol:

# $\int$


comes from an elongated letter **S**, representing **sum**, since integrals add together infinitely many small pieces.

## Real-Life Uses of Integrals

- Finding area under curves
- Calculating velocity and distance
- Measuring volume of objects
- Physics and engineering calculations
- Economics and probability

## Simple Idea

Imagine adding up many tiny pieces to find a total amount.  
That process is essentially what an integral does.



# Basic Rules and Formulas

## 1) Power Rule
For any power where \(n $\neq$ -1\):

$$
\int x^n dx = \frac{x^{n+1}}{n+1} + C
$$

- Add 1 to the exponent
- Divide by the new exponent
- Add \(+C\)

Example:

$$
\int x^2 dx = \frac{x^3}{3}+C
$$

---

## 2) Constant Rule

$$
\int a dx = ax + C
$$

Where \(a\) is a constant.

Example:

$$
\int 5 dx = 5x + C
$$

---

## 3) Constant Multiple Rule

$$
\int a f(x)dx = a\int f(x)\dx
$$

- Constants can be pulled outside the integral.

Example:

$$
\int 3x^2 \, dx
=
3\int x^2 dx
=
x^3 + C
$$

---

## 4) Sum Rule

$$
\int (f(x)+g(x))dx
=
\int f(x)dx
+
\int g(x)dx
$$

Example:

$$
\int (x^2+x)\,dx
=
\frac{x^3}{3}
+
\frac{x^2}{2}
+
C
$$

---

## 5) Difference Rule

$$
\int (f(x)-g(x))dx
=
\int f(x)dx
-
\int g(x)dx
$$

Example:

$$
\int (x^2-4x)\,dx
=
\frac{x^3}{3}
-
2x^2
+
C
$$

---

## 6) Logarithmic Rule

Special case when exponent is \(-1\):

$$
\int \frac{1}{x}dx
=
\ln|x|
+
C
$$

Example:

$$
\int \frac{1}{x}dx
=
\ln|x|
+
C
$$

---

## 7) Exponential Rule

For Euler's number \(e\):

$$
\int e^x dx
=
e^x
+
C
$$

Example:

$$
\int e^x dx
=
e^x
+
C
$$

---

## 8) Basic Trigonometric Integrals

### Sine

$$
\int \sin(x)\,dx
=
-\cos(x)
+
C
$$

### Cosine

$$
\int \cos(x)\,dx
=
\sin(x)
+
C
$$

### Secant Squared

$$
\int \sec^2(x)\,dx
=
\tan(x)
+
C
$$

### Cosecant Squared

$$
\int \csc^2(x)\,dx
=
-\cot(x)
+
C
$$

---

## Notes

- \(C\) is called the **constant of integration**.
- Integration is the **reverse process of differentiation**.
- Always check if a rule has special conditions, like \(n \neq -1\) in the power rule.

