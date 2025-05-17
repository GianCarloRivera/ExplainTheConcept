1. Exponential Distribution // is a continuous probability distribution commonly applied to model the time interval between independent events occurring at a constant mean rate, such as the time between arrivals at a service center or the life of electronic components.
2. Normal Distribution // Also known as the Gaussian distribution, it is a continuous probability distribution which finds wide application in statistics and natural sciences owing to its circularity in real-life occurrences of the phenomenon. The bell-shaped curve, symmetric about the mean, describes the pattern.
3. Poisson Distribution // A discrete probability distribution models the number of occurrences of an event within a set period of time or distance, provided that the events occur independently and at a known constant average rate. This probability distribution depends on a parameter 
λ alone, which is both a mean and a variance of the distributio
4. Binomial Distribution // is a probability distribution that represents the number of successes in a fixed number of Bernoulli trials. The probability distribution can be described using just two parameters: n, the number of trials and p, the probability of success in a single trial
5. Triangular Distribution // is a continuous probability distribution shaped like a triangle and defined by three parameters: the minimum value a, the maximum value b, and c.
6. Lognormal Distribution // is a lognormal distribution for a positive random variable X whose ln(X) is normally distributed. That is, if X is normally distributed. This is a right skewed distribution with a long “tail” to the right, and is often used to model non-negative data that is thought to have a multiplier effect rather than an additive one (such as stock prices, income or measurements of biological molecules).
7. Gamma Distribution // is a continuous probability distribution often used to model waiting times, lifespans, or time until multiple events occur. It is defined by two parameters: the shape parameter
8. Beta Distribution // is a probability density function on 0,1[0,1], so it is a convenient model for probabilities, proportions and percentages. It has two positive shape is a distribution with two positive shape parameters and and ββ that dictate the shape of the distribution. Here, depending on the values of α and B. is beta function normalized it. The average value of the beta distribution
9. Weibull Distribution // is a continuous probability distribution that is frequently used to model lifetimes, failure rates, and reliability for systems or components. It is immensely flexible and capable of representing various types of failure behaviors depending on its shape parameter k and scale parameter λ The probability density The Weibull distribution is frequently exploited in reliability engineering, survival analysis, and weather modeling.
10. Uniform Distribution // The uniform distribution is a kind of continuous probability distribution in which all outcomes in the range are equally likely. This means that every interval of the same length in the distribution has the same probability of occurring. The uniform distribution is defined by two parameters, the minimum value a, and the maximum value b, as well as the probability density function The uniform distribution is generally applied in situations where each outcome in a range is equally likely to happen, like random number generation or modeling situations where no outcomes are favored.
============================================================================================================================================================================

Problem and Solving

1. Exponential Distribution
   Problem: We will calculate the probability of the system will fail within 3 hours and if the average probability rate is 1 failure per hour.

Given:

AFPR = 1 failure per hour
Time x = 3 hours

Formula:

 P ( X ≤ x) = 1 - e^-λx
p ( x ≤ 3) = 1 e^1.3
(calculate the e^1.3 first)
e^-3 = 0.04978706836
P ( X ≤ 3) = 1 - 0.0498 (round off)

Answer: 0.9502
============================================================================================================================================================================
2. Normal Distribution
 Problem: we will calculate the probability of a normal distribution where the mean is 100 and the standard is 15 now we will find the value between of this 85 and 115.

Given:
Mean : 100
Standard: 15
X = 85 and 115

Formula:

   z = (X - u)
       --------
          o       (then let's put the value)
z = (85 - 100)
    ------------ (substitute the 85 - 100)
          15

z = -15 / 15

z = -1

now let's solve the next one which is 115 and 100

z = ( x - u)
   ------------
        o 
z = (115 - 100)
   ------------- (also substitute the 115 to 100)
         15

z = 15 / 15 

Z = 1

P ( Z <- 1) = 0.1587
P (Z < 1) = 0.8413

Answer: 0.6826
============================================================================================================================================================================
3. Poisson Distribution
   on average six people visit a small bookshop everyhour, How likely is it that four clients will show up in the next hour?

Given:
λ = 6
k = 4

Formula"

P ( X = k) = λ^ e ^ -λ
            -----------
                  k!

P ( X = 4) = 6^4e^-6
             ---------
                4!
i will calculate first the 6^4

6^4 = 1296

and next is e^-6

e^-6 = 0.00247875217

and the last is 4!

4! = 24

now let's solve

P( X = 4) 1296 x 0.02478752 
          -------------------
                  24
P = 3.212462592
    ------------
          24

P = 0.1338 (round off) 0.1334
============================================================================================================================================================================
4. Binomial Distribution
     A student completes ten multiple-choice question four possible answer, How likely is it for a pupil to get exactly three question right if they guess on each one?

Given:

n = 10
p = 1/4 or 0.25
k = 3

Formula:

q = 1 - p

q = 1 - 1/4 (solve the p first)

q = 1 - 0.25 = 0.75

p = (x = 3) = (10/3) (0.25)^3(0.75)^10-3

first solve this (10/3)

p = (10!)
  ----------
    3!(10-3)

p = !0!
  -------
  3! X 7!

p = 10 x 9 x 8 x 7!
    ---------------- now we will cancelled the 7!
      3! x 7! 

p = 10 x 9 x 8 
  --------------
       3!

p = 720
  --------
      6

p = 120
============================================================================================================================================================================
5. Triangular Distribution
   A project manager projects that the task will take three to eight days to finish, with six days
being the most likely time frame, what is the task's anticapated completion time?

Given:

z= 3
x = 8
y = 6

Formula:

p = z + x + y
    ----------
        z

p = 3 + 8 + 6
    ---------- add the value of z, x, and y
          3

p = 17 / 3 

p = 5.666 (dound off)
p = 5.67
============================================================================================================================================================================
6. Lognormal Distribution
   The time taken for a specific manufacturing process is lognormal dstributed with parameters u = 2.0 and o = 0.4, what is the expected time for the manufacturing process?

Given:
u = 2.0
o = 0.4

Formula:

p = e^u + o^2
      ---
       2 
o^2 = (0.4)^2 = 0.16 / 2 = 0.08

o^2 = e^2.0 + 0.08 = 7.4690

p = 7.469 (round off) 7.47
p = 7.47
============================================================================================================================================================================
7 Gamma Distribution
   on average, a call center four calls everyhour, Assume that the interval between calls is gamma distributed, how many hours will it be before the next call comes in>

Given:
λ = 4
k = 1

Formula:

p = k / λ

p = 1
   ---
    4

p = 0.25

p = k x λ( which is the 0.25)

p = 1 x 0.25 = 0.25
p = 0.25 per hour
============================================================================================================================================================================
8. Beta Distribution
 A company estimates that the proportion of customers who prefer their new product over
 the old one follows a beta distribution with a parameters of a = 3 and b = 7, what is the expected proportion of customers who prefer the new product?

Given
a = 3
b = 7

Formula:

p = a / a + b

p = 3 / 3 + 7

p = 3 / 10

p = 0.3
============================================================================================================================================================================
9. Weibull Distribution
   A company produces light bulbs and the lifetime of these bulbs is  modeled by a Weibull distribution with paramets of k = 3, λ = 10, what is the expected lifetime of the bulb?

Given:
k = 3
λ = 10

Formula:
 = λ(1 + 4/k)
= 10 (4/3)
= 10 (0.892)
= 10 x 0.892 = 8.92

Answer:
Expected lifetime = 8.92
============================================================================================================================================================================
10. Uniform Distribution
    A random variable Y follows a uniform distribution between 3 and 9. what is the expected value and variance of Y?

Given:
a = 3
b = 9

Formula:
= a + b / 2
= 3 + 9 / 2
= 12 / 2
= 12 / 2 = 6

Value is = 6

For Var
 (b - a) 2 / 12
kunin ang value ng b and a

= (9 - 3)^2 / 12

= 36 /12

= 3

For Variance is = 3
============================================================================================================================================================================




    
