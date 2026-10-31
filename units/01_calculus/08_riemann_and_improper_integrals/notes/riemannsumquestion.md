## Question 1 — Limit of a Sum Using a Riemann Sum

### Topic

**Riemann sums and definite integrals**

This question tests whether we can rewrite a sum as a Riemann sum and then evaluate the corresponding definite integral.

### Question

Evaluate

\[
\lim_{n\to\infty}\sum_{k=1}^{n}\frac{n}{n^2+k^2}.
\]

### Solution

Start by rewriting each term:

\[
\frac{n}{n^2+k^2}
=
\frac{1}{n}\cdot\frac{1}{1+(k/n)^2}.
\]

Therefore,

\[
\sum_{k=1}^{n}\frac{n}{n^2+k^2}
=
\sum_{k=1}^{n}\frac{1}{n}\cdot\frac{1}{1+(k/n)^2}.
\]

This has the standard Riemann-sum form

\[
\sum_{k=1}^{n} f(x_k)\,\Delta x,
\]

where

\[
f(x)=\frac{1}{1+x^2},\qquad
\Delta x=\frac{1}{n},\qquad
x_k=\frac{k}{n}.
\]

As \(n\to\infty\), the sum becomes the definite integral

\[
\int_0^1 \frac{1}{1+x^2}\,dx.
\]

Since

\[
\int \frac{1}{1+x^2}\,dx=\arctan x,
\]

we get

\[
\int_0^1 \frac{1}{1+x^2}\,dx
=
\left[\arctan x\right]_0^1
=
\arctan(1)-\arctan(0)
=
\frac{\pi}{4}.
\]

### Answer

\[
\boxed{\frac{\pi}{4}}
\]

**Correct option: (D)**
```**