# A + B mod C

양의 정수 $A$, $B$, $C$에 대하여 다음이 성립한다.

$A + B \bmod C = (A \bmod C) + (B \bmod C) \bmod C$

## 증명

[[나눗셈 정리]]에 따라 두 정수 $a$, $b$에 대해 $a = bq + r$을 만족하는 정수 $q$, $r (0 \le r \lt b)$이 유일하게 존재한다.

$A = CQ_1 + R_1, B = CQ_2 + R_2$라고 하면
$$
\begin{align}
A + B \bmod C
	&= CQ_1 + R_1 + CQ_2 + R_2 \bmod C \\
	&= C(Q_1 + Q_2) + R_1 + R_2 \bmod C \\
	&= R_1 + R_2 \bmod C \\
	&= (A \bmod C) + (B \bmod C) \bmod C
\end{align}
$$
