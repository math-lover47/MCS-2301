## We have 15 tasks here
### I solve almost all of them

---
#### 1
![image](https://github.com/user-attachments/assets/b03e3c9c-390c-44e8-bd05-981b9c15adb7)

$$
\lambda = 0.7
$$
##### a)
$$
X \sim P_{o}(0.7)
$$
$$
P(X=0) = e^{-0.7} \approx 0.497
$$
##### b)
$$
X \sim P_{o}(2.1)
$$
$$
P(X=2) = e^{-2.1} \cdot \frac{2.1^{2}}{2!}\approx 0.270
$$
##### c)
$$
Y \sim P(6, 0.497)
$$
$$
P(Y=2)\binom{6}{2} \cdot 0.497^{2} \cdot 0.503^{4} \approx 0.237
$$
#### 2
$$
\lambda_{\text{mistakes per chapter}} \quad \to \quad X \sim P_{o}(2.25) 
$$
##### b)
$$
P(X<=1) \approx 0.343
$$
##### c)
$$
P(X_{\text{2 chapters}}>6) = 1 - P(X_{\text{2 chapters}} \leq 6) \approx 0.169 
$$
$$
$$
$$

$$

#### 3
![image](https://github.com/user-attachments/assets/ff1284a8-d6dd-400c-a6b0-9e4bd83ea8b3)

$$
Y \sim P_{o}(\lambda)
$$
$$
P(Y=5) = 1.25 \cdot P(Y=3)
$$
$$
e^{-\lambda}\cdot \frac{\lambda^{5}}{5!} = 
1.25 \cdot e^{-\lambda}\cdot \frac{\lambda^{3}}{3!}
$$
$$
\lambda^{2} = 25 \quad \to \quad \lambda = 5
$$
#### 4
![image](https://github.com/user-attachments/assets/220d1ce4-4c8a-449e-95c0-82e6ce7d2b04)

$$
\lambda = 3 \quad \text{(every 5 minutes)}
$$
$$
X \sim P_{o}(3)
$$
##### a)
$$
i) \text{ Given a mean(avg rate of accurences }\lambda) \text{ and interval of time(space) of those occurences}
$$
$$
ii) \text{ Emails arrive independently }
$$
##### b)
$$
X \sim P_{o}(6)
$$
##### i)
$$
P(X = 7) = e^{-6}\cdot \frac{e^{7}}{7!} \approx 0.138
$$
##### ii)
$$
P(X \geq 8) = 1 - P(X \leq 7) = 1 - (P(X=0)+\dots+P(X=7)) \approx 0.256
$$
#### 5
![image](https://github.com/user-attachments/assets/2dbccb64-a984-4538-a9c4-5a8f16c6d7c0)

##### a) n is large, p is small
##### b)
$$
X \sim P(50, 0.08)
$$
$$
P(X\leq 3) = P(0)+\dots+P(3) \approx 0.425
$$
##### c)
$$
\lambda = mean =n\cdot p = 50 \cdot 0.08 = 4
$$
$$
X \sim P_{o}(4)
$$
$$
P(X\leq 3) = P(0)+\dots+P(3) \approx 0.433
$$
##### c)
$$
\delta = \frac{|0.433-0.425|}{0.425}  \approx 0.0188 \%
$$
#### 7
![image](https://github.com/user-attachments/assets/4b557073-db44-4146-a7ee-f9e38d1549c9)

$$
X \sim P_{o}(2) \quad \to \quad \text{ Since it last 2 hours} \quad \to \quad X \sim P_{o}(4)
$$
$$
P_{o}(X\geq 5) = 1-P(X\leq 4) \approx 0.371
$$
$$
Y \sim P_{binom}(5, 0.371)
$$
$$
P(Y=3) = \binom{5}{3} \cdot 0.371^{3} \cdot (1-0.371)^{2} \approx 0.202
$$
#### 8
![image](https://github.com/user-attachments/assets/cd393ee5-40dc-4d8a-afde-6661686d5ec7)

$$
\lambda \quad \to \quad X \sim P_{o}(2.5) 
$$
##### a)
###### i)
$$
P(X=4) = e^{-2.5}\cdot \left( \frac{2.5^{4}}{4!} \right) \approx 0.134
$$
###### ii)
$$
P(X\geq 4) = 1 - P(X \leq 2) \approx 0.456
$$
##### b)
$$
4\lambda \quad \to \quad Y \sim P_{o}(10) 
$$
$$
P(Y>12) = 1 - P(Y \leq 12) \approx 0.208
$$
##### c)
$$
X \sim P(8, 0.208)
$$
$$
P(Y = 2) = \binom{8}{2}\cdot 0.208^{2} \cdot 0.792^{6} \approx 0.299
$$
#### 9
![image](https://github.com/user-attachments/assets/4f960039-69b4-44a5-a4c4-8d36f55ef684)

$$
\lambda \quad \to \quad X \sim P_{o}(6) 
$$
##### b)
$$
P(X=5) = e^{-6}\cdot \left( \frac{6^{5}}{5!} \right) \approx 0.161
$$
##### c)
$$
Y \sim P(4, 0.161)
$$
$$
P(X=2) = \binom{4}{2} \cdot 0.161^{2} \cdot (1-0.161)^{2} \approx 0.109
$$
#### 10
![image](https://github.com/user-attachments/assets/9e5a61e6-35fe-4daa-9cc8-278e831d66b4)

$$
\lambda_{aisha} \quad \to \quad X \sim P_{o}(1.2) 
$$
$$
\lambda_{biyu} \quad \to \quad X \sim P_{o}(0.8) 
$$
##### a)
$$
P(X_{aisha}\geq 1) \cdot P(X_{biyu}\geq 1) = (1-P(X_{aisha} = 0))\cdot (1-P(X_{biyu} = 0)) =
$$
$$
(1-e^{-1.2}) \cdot (1-e^{-0.8}) \approx 0.385
$$
##### b)
$$
P(X_{aisha \cap biyu} = 3) = e^{-(1.2+0.8)} \cdot \frac{2^{3}}{3!} \approx 0.18
$$
##### c)
$$
Y \sim P(5, 0.18)
$$
$$
P(Y \geq 3) = 1 - P(Y \leq 2) \approx 0.0437
$$
#### 11
![image](https://github.com/user-attachments/assets/330f4079-e97f-4afc-a326-2f8858a17625)

$$
\lambda_{desktop} \quad \to \quad X \sim P_{o}(2.4) 
$$
$$
\lambda_{laptop} \quad \to \quad X \sim P_{o}(1.6) 
$$
##### a)
$$
P(X_{desktop}\geq 2) \cdot P(X_{laptop}\geq 2) = (1-P(X_{desktop} \leq 1))\cdot (1-P(X_{laptop} \leq 1)) \approx 0.329
$$
##### b)
$$
P(X_{desktop \cap laptop} = 6) = e^{-(2.4+1.6)} \cdot \frac{4^{6}}{6!} \approx 0.104
$$
##### c)
$$
Y_{\text{D 2 week}} \sim P_{o}(4.8)
$$
$$
Y_{\text{L 2 week}} \sim P_{o}(3.2)
$$
$$
P(X_{\text{D 2 week} \cap \text{L 2 week}} \leq 6) \approx 0.313
$$
#### 12
![image](https://github.com/user-attachments/assets/857526ec-5899-4862-aa36-44325ad15cd8)

$$
\lambda_{year} \quad \to \quad X \sim P_{o}(15) 
$$
##### a)
$$
\lambda_{6month} \quad \to \quad X \sim P_{o}(7.5) 
$$
$$
P(X<5)\approx 0.132
$$
##### b)
$$
\lambda_{1month} \quad \to \quad X \sim P_{o}(1.25) 
$$
$$
P(X \geq 1) = 1 - P(X = 0) \approx 0.713
$$
##### c)
$$
Y \sim P(6, 0.713)
$$
$$
P(Y = 4) = \binom{6}{4} \cdot 0.713^{4} \cdot 0.287^{2} 
\approx 0.319
$$
#### 13
![image](https://github.com/user-attachments/assets/8c95db41-0d35-42cb-b45d-406322fb9fff)

$$
\lambda_{year} \quad \to \quad X \sim P_{o}(8) 
$$
##### a)
$$
\lambda_{1month} \quad \to \quad X \sim P_{o}\left( \frac{2}{3} \right) 
$$
$$
P(X = 2) = e^{-\frac{2}{3}}\cdot \frac{\left( \frac{2}{3} \right)^{2}}{2!} \approx 0.114
$$
##### b)
$$
P(X \geq 2) =  1 -  P(X \leq 1) \approx 0.144
$$
$$
Y \sim P(4, 0.144)
$$
$$
P(Y = 3) = \binom{4}{3} \cdot 0.144^{3} \cdot 0.856^{1} 
\approx 0.010
$$
#### 14
![image](https://github.com/user-attachments/assets/48f08dbb-1e12-4811-bc23-7caaef24a868)

##### a)
$$
\text{Events are independent and occur at const rate so poisson model is suitable: } P_{\text{per minute}}\left( \frac{240}{60} \right)
$$
##### b)
$$
P(X_{1m} = 8) = e^{-4} \cdot \frac{4^{8}}{8!} \approx 0.0298
$$
##### c)
$$
P(X_{2m} \geq 10) = 1- P(X_{2m} \leq 9)\approx 0.283
$$
#### 15
![image](https://github.com/user-attachments/assets/0dbf7edf-e471-48f1-9112-2698b0ca546f)

##### a)
$$
Mean = \frac{0+23+70+99+96+60+42+21+8}{10+23+35+33+24+14+7+3+1} = \frac{419}{150} \approx 2.793
$$
$$
Variance = \frac{0+23+140+297+384+300+252+147+64}{150} - \left( \frac{419}{150} \right)^{2} \approx 2.911
$$
##### b)
$$
Mean \approx Variance
$$
