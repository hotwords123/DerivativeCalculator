
# Derivative Calculator

This is a simple derivative calculator running in web browsers.

Just enter the expression and click "Calculate Derivative". It will do it on its own.

Click [here](https://hotwords123.github.io/DerivativeCalculator/) for a live demo.

~~~But I would not promise that the results are always correct :)~~~

### Ways to form a valid expression:

 - Both numbers and letters are supported. (x is the independent variable.)
 - Use simple +, -, * and / to calculate. ^ stands for involution.
 - Use square brackets ("[" and "]") to describe a function.
 - The multipliers can be omitted in the absence of ambiguities.
 - Note 1: after that, they will be calculated before divisions.
 - Note 2: the operators has their normal priorities, so remember to use the parentheses "()".
 - Note 3: involutions are calculated from right to left, so use the parentheses to avoid ambiguities.

### Supported functions:

 - `sin[a]`, `cos[a]`, `tan[a]`, `cot[a]` - the trigonometric functions
 - `asin[a]`, `acos[a]`, `atan[a]`, `acot[a]` - the anti-trigonometric functions
 - `ln[a]` - the natural logarithm
 - `log[a,b]` - the base-b logrithm (calculated as `ln[a]/ln[b]`)

### Here are a few examples:

 - `3*x`
 - `2*x+a/b-c^x*d`
 - `sin[ax+b]-log[b,ax]+ln[x]`
 - `4abx-5ax+6-2(x+5)(x-3)+7tan[x]`
 - However, The multiplier in the expression `4x*sin[x]` cannot be ommited,
   for it might be mistaken as a function named "xsin".
 - `4x/8ab` will be considered as `(4*x)/(8*a*b)`.
 - `3a^2b` will be considered as `3*(a^2)*b`.
 - `a^b^c` will be considered as `a^(b^c)`.
 - However, `a^bx^c` has the same meaning as `(a^b)*(x^c)`.

Hope you enjoy it!
