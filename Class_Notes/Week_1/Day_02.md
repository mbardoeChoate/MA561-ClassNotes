[comment]: render
# Day 2 
## Calculating Limits from Limit Laws

### Class Goals

* There are rules to limits that help us compute the limit
* Limits are linear (it works well with sums/differences and scalar multiplication)
* Limits work well with products and division (as long as you aren't dividing by zero)
* Limits of most common functions can be solved by plugging in. Things to watch out for:
  * $\frac{0}{0}$ This could be anything.
  * Piecewise defined functions at the values where you change definitions
* Squeeze theorem

#### Limit Laws

Suppose that $\lim_{x \to a} f(x)$ and $\lim_{x \to a} g(x)$ exist then

| Limit Law               | Formula                                                                                                                     |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| Addition/ Subtraction   | $$ \lim_{x \to a} [f(x) \pm g(x)]= \lim_{x \to a} f(x) \pm \lim_{x \to a} g(x) $$                                           |
|||
| Scalar Multiplication   | $$\lim_{x \to a} cf(x) = c \lim_{x \to a} f(x) $$                                                                           |
|                         |                                                                                                                             |
| Function Multiplication | $$\lim_{x \to a} f(x)g(x) = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$$                                                 |
|                         |                                                                                                                             |
| Function Division       | $$\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{ \lim_{x \to a} g(x)}$$ if $$\lim_{x \to a} g(x)\neq 0$$    |
|                         |                                                                                                                             |
| Product Law             | $$\lim_{x \to a} [f(x)]^{n}=[\lim_{x \to a} f(x)]^{n}$$ $n$ is a positive integer                                           |
|                         |                                                                                                                             |
| Root Law                | $$  \lim_{x \to a} \sqrt[n]{f(x) }= \sqrt[n]{ \lim_{x \to a} f(x) }$$ $n$ is a positive integer and if $n$ is even $f(x)>0$ |  


#### Consequences of Limit Laws

For every function that is a polynomial or rational function, if you are trying to evaluate the limit by substitution 
then you can do so as long as the value is in the domain. 

#### Squeeze Theorem

First  we look at a supporting idea:

If $$f(x) \leq g(x)$$ when $x$ is near $a$ (except possibly $a$) and the limits of both $f$ and $g$ exist as $x$ 
approaches $a$ then $$\lim_{x \to a} f(x) \leq \lim_{x \to a} g(x)$$

**Squeeze Theorem**

If $$f(x) \leq g(x) \leq h(x)$$ and if $$\lim_{x \to a} f(x)=\lim_{x \to a} h(x)=L$$

Then $$\lim_{x \to a} g(x)=L$$ 

##### Example Problem

Find the limit of $$\lim_{x \to 0} x^2 \sin(\frac{1}{x})$$

#### More Examples for Students to work on

TK