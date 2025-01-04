## We have 13 tasks here
### I solve all of them

---
#### 1
##### a
$$
P(X=20) = \binom{30}{20} \cdot 0.75^{20} \cdot 0.25^{30-20} \approx 0.0909
$$
##### b
$$
P(X\leq 13) =P(X=0) + \dots +P(X = 13) \approx 0.000216
$$
##### c
$$
P(12 \leq X \leq 25) =P(X=12) + \dots +P(X = 25) \approx 0.902
$$
#### 2
##### a
$$
P_{geo}(6) =  \left( \frac{2}{3} \right)^{5} \cdot \left( \frac{1}{3} \right) \approx 0.0439
$$
##### b
$$
X \sim B\left( 8, \frac{1}{3} \right) 
$$
$$
P(X=2) = \binom{8}{2} \cdot \left( \frac{2}{3} \right)^{6} \cdot \left( \frac{1}{3} \right)^{2} \approx 0.273
$$
#### 3
##### a
$$
P(X=0) = \binom{12}{0} \cdot 0.3^{0} \cdot 0.7^{12} \approx 0.0138
$$
##### b
$$
P(X>2) = P(X \leq 2) = P(X=0) + P(X=1) +P(X=2) \approx 0.7472
$$
#### 4
##### a

1. Fixed number of trials
2. Continuous probability of success
3. Number of successes and failures are known 

##### b
$$
P(X\geq 2) = 1 - P(X\leq 1) = 1 - ((0.5^{0} \cdot 0.95^{10})+(0.5^{1} \cdot 0.95^{9})) \approx 0.861
$$
##### c
$$
P(\text{at least 1 success}) = 1 - P(\text{no success)} >0.99
$$
$$
1 - (0.95)^{n} > 0.99
$$
$$
0.95^{n} < 0.01
$$
$$
n > \frac{\ln 0.01}{\ln 0.95} \approx 89.781
$$
$$
n = 90
$$
#### 5
##### a
$$
0.5^{10} \approx 0.000977
$$
##### b
$$
P(X\geq 8) = 
0.5^{8} \cdot 0.5^{2} \cdot \binom {10}{8} + 
0.5^{9} \cdot 0.5^{1} \cdot \binom {10}{9} + 
0.5^{10} \cdot 0.5^{0} \cdot \binom {10}{10}
\approx 0.0547
$$
#### 6
##### a
$$
x+x+x+x+x+2x=1 \quad \to \quad x = \frac{1}{7}
$$

$$
P_{geo}(X=6) = \left( \frac{5}{7} \right)^{5} \cdot \left( \frac{2}{7} \right) \approx 0.0531
$$
##### b
$$
X \sim P\left( 8, \frac{2}{7} \right)
$$
$$
P_{binom}(X=5) = \binom{8}{5} \cdot
\left( \frac{2}{7} \right)^{5} \cdot 
\left( \frac{5}{7} \right)^{2}
\approx 0.243
$$
#### 7
##### b
$$
X \sim P(10, 0.15) 
$$
$$
P(X\geq 5) = 1 - P(X \leq 4) = 0.00987
$$
##### c
$$
P(X=2) = \binom{10}{2} \cdot 0.15^{2} \cdot 0.85^{8} \approx 0.276
$$
#### 8
$$
X \sim P(20, 0.45) 
$$
##### a
$$
P(X\leq 12) = P(X=0)+\dots +P(X=12) \approx 0.869
$$
##### b
$$
P(X = 12) = \binom{20}{12} \cdot (0.45)^{12} \cdot (0.55)^{8} \approx 0.0727
$$
#### 9
$$
X \sim P(20, 0.6) 
$$
##### a
$$
P(X\geq 20 \cdot 0.5) = 1 - P(X\leq 9) \approx 0.872
$$
$$
Y \sim P(12, 0.872) 
$$
##### b
$$
P(Y=7) = \binom{12}{7}\cdot (0.872)^{7}\cdot (0.128)^{5} \approx 0.0104
$$
##### c
$$
P(Y<6 ) = P(Y=0) +\dots +P(Y=5) 
\approx 0.000247
$$
#### 10
$$
X \sim P(20, 0.075) 
$$
##### a
###### i
$$
P(X = 2) = \binom{20}{2} \cdot 0.075^{2} \cdot (1-0.75)^{18} \approx 0.263
$$
###### ii
$$
P(X \geq 4) = 1 - P(X\leq 3) \approx 0.0582
$$
##### b
$$
Mean = n\cdot p = 80\cdot 0.075 = 6
$$
$$
\sigma^{2} = n\cdot p\cdot(1-p)=6\cdot(1-0.075) = 5.55
$$
#### 11
$$
X \sim P(10, 0.02)
$$
##### a
$$
P(X>1) = 1 - P(X\leq 1) = 1 - 
(\binom{10}{0}\cdot 0.02^{0}\cdot 0.98^{10}+
\binom{10}{1}\cdot 0.02^{1}\cdot 0.98^{9}) \approx
0.0162
$$
##### b
$$
X \sim P(500, 0.02)
$$
$$
Mean = 500\cdot 0.02=10
$$
$$
\sigma = 10\cdot 0.98 = 9.8
$$
#### 12
$$
X \sim P(10, 0.025)
$$
$$
P(X=2)=\binom{10}{2}\cdot 0.025^{2}\cdot 0.975^{8} \approx 0.0230
$$
$$
X \sim P(120, 0.025)
$$
$$
Mean = 120 \cdot 0.025 = 3
$$
$$
\sigma^{2} = 120 \cdot 0.025 \cdot (1 - 0.025) = 2.925 
$$
#### 13
$$
X \sim P(2n, 0.25)
$$
$$
P(X \geq n) \leq 0.1
$$
$$
1 - P(X < n) \leq 0.1
$$
$$
P(X < n) \geq 0.9 \quad \text{Just substitute values}
$$
$$
 \text{Smallest n is 5: } 0.0996
$$