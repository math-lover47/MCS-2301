Please write me in telegram  if you solve something I couldn't solve, then I'll fix it here.

![image](https://github.com/user-attachments/assets/cb90f94c-e7d0-4a3b-9441-d7a877ab5002)


![image](https://github.com/user-attachments/assets/7d845c8b-4fec-4ae3-9e91-334585edcb0f)


![image](https://github.com/user-attachments/assets/fa5615f8-0206-44ba-a5e7-64928f69eeba)

![image](https://github.com/user-attachments/assets/5e1f786b-720a-430d-875e-3642c0339ad1)

# Shortly how I did it:

$$
\begin{aligned}
\Large P(9 \leq X < 9+3) -> P(9 \leq X \leq 11) \\ \\
\Large = P(X=9) +  P(X=10) +  P(X=11) 
\end{aligned}
$$

$$
\Large P(X=9) = e^{-9} \left( \frac{9^{9}}{9!} \right) = 0.131,756
$$

$$
\Large P(X=10) = e^{-9} \left( \frac{9^{10}}{10!} \right) = 0.118,58
$$

$$
\Large P(X=11) = e^{-9} \left( \frac{9^{11}}{11!} \right) = 0.097,020,1
$$

$$
\begin{aligned}
\Large P(9 \leq X \leq 11) = 0.131756 + 0.11858+0.0970201 = 0.347,256,1 \approx \\ \Large0.347 
\end{aligned}
$$

$$
\Large P(X\leq 9-3) = P(X \leq 6) = 
$$

$$
\Large e^{-9} \left( \frac{9^{0}}{0!}+\frac{9^{1}}{1!}+\frac{9^{2}}{2!}+\frac{9^{3}}{3!}+\frac{9^{4}}{4!}+\frac{9^{5}}{5!}+\frac{9^{6}}{6!} \right) = 0.2067808399\approx 0.207
$$

![image](https://github.com/user-attachments/assets/f29932ef-0961-4c08-9488-9948ef5ef9a3)


![image](https://github.com/user-attachments/assets/6ff6f42a-ba26-4cbc-82dd-7e5641232b23)


![image](https://github.com/user-attachments/assets/94de2773-4025-413e-990b-dbc2e09058e5)


![image](https://github.com/user-attachments/assets/cd43ed3c-60ad-4799-8f92-f0666161b742)


![image](https://github.com/user-attachments/assets/a682cc8d-7848-43cd-829f-2d752b49aed2)

# Shortly how I did it:

$$
\Large \lambda = n * p = 80*0.1=8
$$

$$
\Large P(X\geq 1) = 1 - P(X=0)= 1- e^{-8} = 0.9996645374 \approx 1  
$$

$$
\Large e^{-8} \left( \frac{8^{0}}{0!}+\frac{8^{1}}{1!}+\frac{8^{2}}{2!}+\frac{8^{3}}{3!}+\frac{8^{4}}{4!}+\frac{8^{5}}{5!}+\frac{8^{6}}{6!} \right) = 0.3133742775 \approx 0.313
$$

![image](https://github.com/user-attachments/assets/a790ee67-6ca2-46ef-be24-fd50235e2709)

# Shortly how I did it:

$$
\begin{aligned}
\Large 12 - 1 \\
\Large 1 - x \\ \\
\Large x = \frac{1}{4}
\end{aligned}
$$

$$
\Large P(X\geq 2) = 1 - P(X\leq1)=1-e^{-\frac{1}{4}\left( 1+\frac{1}{4} \right)}= 0.26499 \approx 0.0265
$$

$$
\begin{aligned}
\Large P(\text{Crossing Installed}) = 1 - (P\leq1)^{12} = 1-\left( e^{-\frac{1}{4}\left( 1+\frac{1}{4} \right)} \right)^{12}=  \\ \\
\Large 0.275,502,801,6 \approx 0.2755 \\
\Large \text{(I tried both 3 d.p and 4 d.p)}
\end{aligned}
$$

![image](https://github.com/user-attachments/assets/a9cc09ff-ab15-4e1d-a84a-c273196b6a10)

# Shortly how I did it:

$$
\Large P(X\geq 1) = 1 - P(X=0)=1-e^{-0.2}= 0.1812692469 \approx 0.1813
$$

$$
\Large P(Y = k) = \binom{n}{k} * p^{k} * (1 - p)^{n-k}
$$

$$
\Large P(Y <2 ) = P(Y=0)+P(Y=1)
$$

$$
\Large \binom{30}{0} * 0.1813^{0}*(1 - 0.1813)^{30 - 0} + \binom{30}{1} * 0.1813^{1} * (1 - 0.1813)^{30 - 1} 
$$

$$
\Large =0.01892490291 \approx 0.0189 \\
\text{(Try 0.01892)}
$$
