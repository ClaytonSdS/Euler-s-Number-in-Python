# Euler's Number in Python
A comparative approach about the values provided by Python libraries for the Euler's number, in relation to the approximate value of e by a Taylor polynomial.

## Taylor Polynomial.
$$
\\text{f(x)} = e^x ≈ f(x_0) + \\frac{df(x_0)}{dx} (x-x_0) + \\frac{d^2f(x_0)}{dx^2} \\frac{(x-x_0)^2}{2!} + ...  + \\frac{d^nf(x_0)}{dx^n} \\frac{(x-x_0)^n}{n!}   
$$

#### Therefore
$$
\\text{f(x)} = e^x ≈ e^0 + e^0(x-0) + e^0\\frac{(x-0)^2}{2!} + ...  + e^0\\frac{(x-0)^n}{n!} = 1 + x + \\frac{x^2}{2!} + ...  + \\frac{x^n}{n!} = P_n(x)
$$

#### Python Code

#### Conclusions
From the results, the determined value of e (in Python) is between $P(16) < e_{\text{python}} < P(17)$, with a maximum error of ≤ $4.25 \times 10^{-16}$.
