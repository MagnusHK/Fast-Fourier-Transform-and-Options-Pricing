# Fast-Fourier-Transform-and-Options-Pricing

Pricing derivates is an important part of quantitative finance. However, it can be complicated. Over the years, several methods have been researched and developed, one of the more well-known result is the Black-Scholes model, also known as the Black-Scholes-Merton model (1973), which is used for pricing European options.
Because of computational complexity several other methods have been proposed, for instance, the Fast Four Fourier Transform (FFT) have gained popularity because of its computational efficiency. 

By using the Fourier Transform of the Black-Scholes model it can be solved more efficiently, since it makes it possible to compute the prices for different strike prices at once. This is done by discretizing the problem and then use the FFT to solve the equation in the frequency domain. 

## The Fourier Transform
First we consider the Fourier transform. Let $f(x)\in L^1(\mathbb{R})$ be a piecewise continous and real function for $x \in (-\infty, \infty)$, such that
$$\int_{-\infty}^{\infty}$$







