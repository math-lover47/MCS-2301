## We have 21 tasks here
### I solve all of them

---
#### 1
![image](https://github.com/user-attachments/assets/97287ffc-95c7-4dcd-8491-3d8a1917065f)

##### a)
```
    Y
   /
  Y
 / \
/   B
0   
\   B
 \ /
  Y
   \
    Y
```
##### b)
$$
P(B \cup B) = \frac{3}{7} * \frac{2}{6} = \frac{1}{7}
$$
##### c)
$$
P((B \cup Y )\cap(B\cup Y) ) = \frac{4}{7} * \frac{3}{6} + \frac{3}{7} * \frac{4}{6} = \frac{4}{7}
$$
#### 2
![image](https://github.com/user-attachments/assets/bb0be0fc-484b-4042-9a41-598d9b341f75)

```
  R
 / 
/   
0 ----G  
\  
 \ 
  B
```
##### b)
$$
P((R \cap R \cap B)\cup(R \cap R \cap G)) ) = \frac{7}{15}\frac{7}{15}\left(\frac{3}{15}+\frac{5}{15}\right)=0.175
$$
##### c)
$$
P((R \cap G \cap B) (3!) = \frac{7}{15}\frac{5}{15}\frac{3}{15} (3!) = 0.093
$$
#### 3
![image](https://github.com/user-attachments/assets/e794c4b6-f542-4099-a3a6-0318651e030d)

##### a)
$$
P((B \cap B \cap B) = 0.391^{3}  = 0.0397
$$
##### b)
$$
P((B' \cap B' \cap B') = (1-0.391)^{3}  = 0.286
$$
##### c)
$$
1-P((B' \cap B' \cap B') = 1- (1-0.391)^{3}  = 0.724
$$
#### 4
![image](https://github.com/user-attachments/assets/32f247d5-cf74-43b7-9ddc-c0c71f9ab9f4)


##### a)
$$
P(Y=11) = \frac{\sum f_{11}}{n} = \frac{128}{250}=0.512
$$
##### b)
$$
P(S<35) = \frac{15+28+37}{250}=\frac{8}{25}=0.32
$$
##### c)
$$
15 \quad x \quad 18
$$
$$
30 \quad 34 \quad 35
$$

$$
x = 15+3\left( \frac{34-30}{35-30} \right) = 15 + 3*0.8 \approx 17
$$

$$
P(Y=10 \cap (25 \leq S \cap S\leq 34)) = \frac{17+13}{250} = \frac{3}{25}=0.12
$$

##### d)
$$
18 \quad x_{10} \quad 25
$$
$$
35 \quad 37 \quad 40
$$

$$
x_{10} = 18+7\left( \frac{37-35}{40-35} \right) = 18 + 7*0.4 \approx 21
$$

$$
19 \quad x \quad 30
$$
$$
35 \quad 37 \quad 40
$$

$$
x_{11} = 19+11\left( \frac{37-35}{40-35} \right) = 19 + 11*0.4 \approx 23
$$

$$
P(pass) = \frac{(21+30+27)+(23+26+32)}{250} = \frac{159}{250} \approx 0.636
$$

#### 5
![image](https://github.com/user-attachments/assets/f594ebf5-3528-482d-b906-751a9cb566a1)

##### a) 
$$
P(X>=3) = \frac{50-1*6}{50} = 0.88
$$
##### b)

$$
P(X<=3.75) = \frac{1 * 6+0.5 * 50 + 0.25 * 30}{50} = 0.77
$$
#### 6

##### a) 
```S
T=35                      9                        F=54
++---------------++--------------++---------------++
||       18      ||       5      ||        35     ||
||   ++----------||--------------||----------++   ||
||   ||          ||              ||          ||   ||
||   ||     8    ||       4      ||    10    ||   ||
||   ||          ||              ||          ||   ||
++---||----------++-------------++-----------||---++
  12 ||                  40                  || 14
     ||                                      ||
     ++--------------------------------------++
                          S=62
                          
T'F'S'=150-(62+58)=150-120=30
```
##### b)
$$
P(T'F'S') = \frac{30}{150}=\frac{1}{5}=0.2
$$

$$
P(\text{No more than one cartoon}) = \frac{18+35+40+30}{150}=\frac{123}{150}=\frac{41}{50}=0.82
$$
#### 7

##### a)

```S
A = 1/3              A U B = 1/2             B = 1/4
++---------------++--------------++---------------++
||               ||              ||               ||
||               ||              ||               ||
||      1/4      ||      1/12    ||       1/6     ||
||               ||              ||               ||
||               ||              ||               ||
++---------------++--------------++---------------++
                          
A'B'= 1 - 6/12 = 0.5
```
$$
P(A \cap B) = P(A)+P(B)-P(A \cup B) = 
\frac{1}{3} + \frac{1}{4} - \frac{1}{2} = \frac{1}{12}
$$
$$
P(A) = \frac{1}{3}-\frac{1}{12} = \frac{1}{4} \quad 
P(B) = \frac{1}{4}-\frac{1}{12} = \frac{1}{6}
$$
##### b)
$$
P(A \cap B) = P(A) \cdot P(B)
$$
$$
\frac{1}{12} = \frac{1}{3} \cdot \frac{1}{4} \quad
\text{So its independent}
$$
#### 8

```S
C                              F                             S
++------------++-------++------------++-------++------------++
||            ||       ||            ||       ||            ||
||            ||       ||            ||       ||            ||
||     8      ||   13  ||      4     ||   5   ||      7     ||
||            ||       ||            ||       ||            ||
||            ||       ||            ||       ||            ||
++------------++-------++------------++-------++------------++
```
##### a)
$$
P(C \cap S) = 0 \quad \text{C and S are mutually exclusive}
$$
##### b)
$$
P(C \cap F) = P(C) \cdot P(F)
$$
$$
\frac{13}{38} = \frac{21}{38} \cdot \frac{22}{38} \quad \text{Not independent}
$$

#### 8

##### a)

```S
J                    J U K = 0.5                   K
++---------------++--------------++---------------++
||               ||              ||               ||
||               ||              ||               ||
||      0.25     ||      0.05    ||       0.2     ||
||               ||              ||               ||
||               ||              ||               ||
++---------------++--------------++---------------++
                          
J'K'= 1 - 0.5 = 0.5
```
##### b)
$$
P(K \cap J) = P(K) \cdot P(J)
$$
$$
0.05 = 0.25 \cdot 0.2 \quad \text{Independent}
$$
#### 10

##### a)
$$
P(P \cap T) = P(P)+P(T)-P(P \cup T) = \frac{85+60-95}{100} = \frac{50}{100}
$$
##### b)
```S
P = 85                                        T = 60
++---------------++--------------++---------------++
||               ||              ||               ||
||               ||              ||               ||
||      35       ||      50      ||       10      ||
||               ||              ||               ||
||               ||              ||               ||
++---------------++--------------++---------------++
                          
P'T'= 5 So logically P U T = 1- P'T' = 95
```
c)
$$
P(\text{only P}) = \frac{35}{100} = 0.35
$$
d)
$$
P(P \cap T) = P(P) \cdot P(T)
$$
$$
\frac{50}{100} \neq \frac{35}{100} \cdot \frac{10}{100} \quad \text{Not independent}
$$

#### 11

##### a)
$$
P(A \cap B) = P(A)+P(B)-P(A \cup B) 
$$
$$
x = (x+0.3) + (x+0.4)-0.85
$$
$$
x = 0.15
$$
$$
P(A \cap B) = P(A) \cdot P(B) 
$$
##### b)

$$
0.15 \neq 0.45 \cdot 0.55 \quad \text{Not independent}
$$
#### 12

##### a)
```
       C3                C1 = 4/5     C'1 = 1/5
      /                  C2 = 2/3     C'2 = 1/3
    C2 ---C'3            C3 = 1/2     C'3 = 1/2
   /
  C1---C'2 ---C3
 /        \
/          C'3
0
\         C3
 \       /
  C'1---C2 ---C'3
   \
    C'2 ---C3
     \
      C'3
```
##### b)
###### i)
$$
P(C_{1} \cap C_{2} \cap C_{3}) = 
\frac{4}{5} \cdot \frac{2}{3} \cdot \frac{1}{2} = \frac{4}{15}
$$
###### ii)
$$
P(C_{1} \cap C_{2}' \cap C_{3}') \cup P(C_{1}' \cap C_{2} \cap C_{3}') \cup P(C_{1}' \cap C_{2}' \cap C_{3}) =
$$
$$
\left( \frac{4}{5} \cdot \frac{1}{3} \cdot \frac{1}{2}  \right)+
\left( \frac{1}{5} \cdot \frac{2}{3} \cdot \frac{1}{2}  \right)+
\left( \frac{1}{5} \cdot \frac{1}{3} \cdot \frac{1}{2}  \right) 
= \frac{7}{30}
$$
##### c)
$$
P(\text{at least 2}) = 1 - (P(\text{only 1}) + P(\text{none}))=
$$
$$
1 - \left( \frac{7}{30} + \frac{1}{30}\right) 
= \frac{22}{30} 
= \frac{11}{15}
$$
#### 13

##### a)

```
     F
    /                        P(A) = 0.16
   /                         P(B) = 0.50
  A --- F'        F          P(C) = 0.34 
 /               /
/               /            P(A and F) = 0.04  P(A and F') = 0.96
0 -------------B             P(B and F) = 0.03  P(B and F') = 0.97
\               \            P(C and F) = 0.07  P(C and F') = 0.93
 \               \
  C --- F         F'
   \
    \
     F'
```
##### b)
###### i)
$$
P(B \cap F) = 0.50 \cdot 0.03 = 0.015
$$
###### ii)
$$
P(A \cap F) \cup P(B \cap F) \cup P(C \cap F) =
$$
$$
0.16 \cdot 0.04 + 0.50 \cdot0.03 +0.34 \cdot 0.07 =
0.0452
$$

#### 14

##### a)
$$
P(A \cup B) = P(A)+P(B)-P(A \cap B) = 0.40+0.35 - 0.20 = 0.55
$$
##### b)
$$
P(A' \cap B') = 1-P(A \cup B) = 1 - 0.55 = 0.45
$$
##### c)
$$
P(B|A) = \frac{P(B \cap A)}{P(A)} = \frac{0.2}{0.4} = \frac{1}{2} = 0.5
$$
##### d)
$$
P(A'|B) = \frac{P(B \cap A')}{P(B)} 
= \frac{0.35-0.20}{0.35} 
= \frac{0.15}{0.35} 
= \frac{3}{7}
$$
#### 15

##### a)

```S
J=25                         K=45                         L=15
++------------++-------++------------++-------++------------++
||            ||       ||            ||       ||            ||
||            ||       ||            ||       ||            ||
||     15     ||   10  ||    28.25   ||  6.75 ||    8.25    ||
||            ||       ||            ||       ||            ||
||            ||       ||            ||       ||            ||
++------------++-------++------------++-------++------------++

                          
A'B'= 1 - (45+15+8.25) = 31.75
```
$$
P(K \cap L) = P(K) \cdot P(L)   
$$
$$
P(K \cap L) = 0.45 \cdot 0.15 = 0.0675
$$
##### b)
###### i)
$$
P(J \cup K) = \frac{45+15}{100} =0.6 
$$
###### ii)
$$
P(J' \cup L') = \frac{31.75+28.25}{100} = 0.6
$$
###### iii)
$$
P(J|K) = \frac{P(J \cap K)}{P(K)} = \frac{10}{45} = \frac{2}{9} \approx 0.222
$$
###### iv)
$$
P(K|(J' \cap L')) = \frac{P(K \cap (J' \cap L'))}{P(J')\cap P(L')}
= \frac{28.75}{31.75+28.75} = \frac{28.25}{60} \approx 0.471
$$

#### 16

##### a)
$$
P(\text{study 1 subject}) = \frac{8+18}{60} = \frac{13}{30}
$$
##### b)
$$
P(F|S) = \frac{P(F \cap S)}{P(S)} = \frac{27}{45} = \frac{3}{5}
$$
##### c)
$$
P(S|F') = \frac{P(S \cap F')}{P(F')} = \frac{18}{25} 
$$
##### d)
$$
P(\text{one language}) \cdot P(\text{wear glasses}) = \frac{26}{60} \cdot \frac{8 \cdot 0.75 + 18 \cdot 0.5}{60} = \frac{13}{120}
$$
##### d)

$$
P(\text{wear glasses}|\text{one language}) 
= \frac{P(\text{wear glasses} \cap \text{one language})}{P(\text{one language})} = \frac{8 \cdot 0.75 + 18 \cdot 0.5}{18+8} 
= \frac{15}{26} 
$$
#### 17

##### a)

```
    R          R = 6   G = 9     Total = 15 (Not replaced)
   /
  R
 / \
/   G
0   
\   R
 \ /
  G
   \
    G
```

##### b)
###### i)
$$
P(G_{1} \cap G_{2}) = \frac{9}{15} \cdot \frac{8}{14} = \frac{12}{35}
$$
###### ii)
$$
P(G_{1} \cap R_{2}) \cup P(R_{1} \cap G_{2}) 
= \frac{9}{15} \cdot \frac{6}{14} 
+ \frac{6}{15} \cdot \frac{9}{14} 
= \frac{9 \cdot 2}{35} = \frac{18}{35}
$$
##### c)
$$
P(R_{1} \cap R_{2} \cap R_{3}) \cup 
P(R_{1} \cap G_{2} \cap R_{3}) \cup 
P(G_{1} \cap R_{2} \cap R_{3}) \cup 
P(G_{1} \cap G_{2} \cap R_{3}) =
$$
$$
\frac{6 \cdot 5 \cdot 4}{15 \cdot 14 \cdot 13} + 
\frac{6 \cdot 9 \cdot 5}{15 \cdot 14 \cdot 13} + 
\frac{9 \cdot 6 \cdot 5}{15 \cdot 14 \cdot 13} + 
\frac{9 \cdot 8 \cdot 6}{15 \cdot 14 \cdot 13} =
\frac{182}{35 \cdot 13} = \frac{14}{35} = \frac{2}{5} = 0.4
$$
##### d)
$$
P(G_{1} \cap G_{2} \cap G_{3} \cap G_{4}) =
\frac{9 \cdot 8 \cdot 6 \cdot 5}{15 \cdot 14 \cdot 13 \cdot 12} = \frac{6}{65}
$$
#### 18

```
    W          
   /
  W
 / \
/   L
0   
\   W
 \ /
  L
   \
    L
```
##### a)
$$
P(W_{1} \cap W_{2}) \cup P(L_{1} \cap L_{2}) = (0.7 \cdot 0.8) + (0.3 \cdot 0.6) = 0.74
$$
##### b)
$$
P(\text{Win|2 set}) = \frac{0.56}{0.74} = \frac{28}{37} \approx 0.757
$$
##### c)
$$
P(W_{1} \cap W_{2}) \cup P(W_{1} \cap L_{2}) \cup P(L_{1} \cap W_{2}) = 0.55((0.7 \cdot 0.8) + (0.3 \cdot 0.4) + (0.7 \cdot 0.2))
=0.703
$$
#### 19

```S
B = 41                                        W = 29
++---------------++--------------++---------------++
||               ||              ||               ||
||               ||              ||               ||
||      26       ||      15      ||       14      ||
||               ||              ||               ||
||               ||              ||               ||
++---------------++--------------++---------------++
                          
B'W' = 75 - (41 + 14) = 20
```
##### a)
$$
P(B' \cap W') = \frac{20}{75} = \frac{4}{15} \approx 0.267
$$
##### b)
$$
P((B \cap W)| B) = \frac{15}{41} \approx 0.366
$$
##### c)
$$
P(B_{1} \cap B_{2}) = \frac{26}{75} \cdot \frac{25}{74} = \frac{13}{111} \approx 0.267
$$
##### d)
$$
P(\text{both have W paws}) = 
\frac{29}{75} \cdot \frac{28}{74} = 
\frac{406}{2775} = \frac{13}{111}
$$
#### 20

##### a)
$$
P(A \cap B) = P(A) \cdot P(B)
$$
$$
0.12 = 0.4 \cdot P(B) \quad \to \quad P(B) = 0.3
$$
##### b)
$$
P(A' \cap B') = \frac{42}{100} = 0.42
$$
##### c)

```S
A                             B                              C
++------------++-------++------------++-------++------------++
||            ||       ||            ||       ||            ||
||            ||       ||            ||       ||            ||
||     28     ||  12   ||     8      ||  10   ||     30     ||
||            ||       ||            ||       ||            ||
||            ||       ||            ||       ||            ||
++------------++-------++------------++-------++------------++

                          
A'B'C'= 100 - (30 + 28 + 30) = 12
A'B' = 100 - (40 + 18) = 42 
```
##### d)
###### i)
$$
P(B|C) = \frac{P(B \cap C)}{P(C)} = \frac{10}{40} = 0.25 
$$
###### ii)
$$
P(A \cap (B' \cup C)) = P(\text{only A}) = \frac{28}{100} = 0.28
$$
#### 21

##### a) 
because in many matches neither teams scores the probability doesn't add up to 1.
##### b)
$$
P(A \cap W) = P(A) \cdot P(W)
$$
$$
0.6 \cdot P(W) = 0.48 \quad \to \quad P(W) = 0.8
$$
$$
P(A \cap W') = P(A) \cdot P(W') = 0.6 \cdot (1-0.8) = 0.48 
$$
##### c)

$$
P(W|B) = \frac{P(W \cap B)}{P(B)}
$$
$$
P(W \cap B) = 0.35 \cdot 0.3 = 0.105 = P(W \cap A')
$$
$$
\text{We know that : } P(A \cap W) = 0.48
$$
$$
P(W) = P((W \cap A') \cup (W \cap A)) = 0.105 + 0.480 = 0.585
$$
$$
P(A'|W) = \frac{P(W\cap A')}{P(W)} = \frac{0.105}{0.585} \approx 0.179
$$