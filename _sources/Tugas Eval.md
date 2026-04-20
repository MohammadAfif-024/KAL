# Tugas Evaluasi Determinan Dan Invers


## 1. Matriks 2×2
$$
A =
\begin{bmatrix}
-7 & 1 \\
-5 & 4
\end{bmatrix}$$

Ekspansi baris pertama (i = 1):  
$$det(A)=a11​C11​+a12​C12​$$

Minor:

$$
M_{11} = 4, \quad M_{12} = 1
$$


Kofaktor:
$$
\det(A) = a_{11}C_{11} + a_{12}C_{12}
$$

Determinannya:
$$det(A)=(−7)(4)+(−5)(−1)=−28+5=−23​$$

## 2. Matriks 3×3
$$
A =
\begin{bmatrix}
0 & 1 & 0 \\
2 & -2 & 0 \\
-3 & -1 & 1
\end{bmatrix}$$

Ekspansi baris pertama: 
$$\
det(A) = a_{11}C_{11} + a_{12}C_{12} + a_{13}C_{13}
$$

### a. Elemen a11 =0
Minor: $$
M_{11} =
\begin{vmatrix}
-2 & 0 \\
-1 & 1
\end{vmatrix}
= (-2)(1) - (-1)(0) = -2
$$

Kofaktor:
$$
C_{13} = (+) M_{13} = 0
$$
Kontribusi: $$0⋅(−2)=0$$

### b. Elemen a12=2
Minor:
$$M_{12} =
\begin{vmatrix}
1 & 0 \\
-1 & 1
\end{vmatrix}
= (1)(1) - (-1)(0) = 1
$$
Kofaktor:
$$C12​=(−)(1)=−1$$
Kontribusi:
$$2⋅(−1)=−2$$

### c. Elemen a13=−3
Minor:
$$
M_{13} =
\begin{vmatrix}
1 & 0 \\
-2 & 0
\end{vmatrix}
= (1)(0) - (-2)(0) = 0
$$
Kofaktor:
$$C13​=(+)(0)=0$$
Kontribusi:
$$−3⋅0=0$$

### Hasil =
$$det(A)=0−2+0=0​$$

## 3. Matriks 4×4
$$
A =
\begin{bmatrix}
1 & -3 & 1 & 1 \\
-3 & 1 & 1 & 1 \\
1 & 1 & -3 & 1 \\
1 & 1 & 1 & -3
\end{bmatrix}
$$
Ekspansi baris pertama:
$$det(A)=a11​C11​+a12​C12​+a13​C13​+a14​C14​$$

### a. Elemen a11 = 1
Minor:
$$
M_{11} =
\begin{vmatrix}
1 & 1 & 1 \\
1 & -3 & 1 \\
1 & 1 & -3
\end{vmatrix}
= 1
\begin{vmatrix}
-3 & 1 \\
1 & -3
\end{vmatrix}
- 1
\begin{vmatrix}
1 & 1 \\
1 & -3
\end{vmatrix}
+ 1
\begin{vmatrix}
1 & -3 \\
1 & 1
\end{vmatrix}
$$

Hitung (Sarrus):
$$=1((−3)(−3)−1⋅1)−1(1(−3)−1⋅1)+1(1⋅1−(−3)⋅1)
=1(9−1)−1(−3−1)+1(1+3)
=8+4+4=16$$
Kofaktor: $$C11​=+16$$
Kontribusi: $$1⋅16=16$$

### b. Elemen a12= -3
Minor: $$
M_{12} =
\begin{vmatrix}
-3 & 1 & 1 \\
1 & -3 & 1 \\
1 & 1 & -3
\end{vmatrix}
= -3
\begin{vmatrix}
-3 & 1 \\
1 & -3
\end{vmatrix}
- 1
\begin{vmatrix}
1 & 1 \\
1 & -3
\end{vmatrix}
+ 1
\begin{vmatrix}
1 & -3 \\
1 & 1
\end{vmatrix}
$$
Hitung (Sarrus):
$$=(−3)((−3)(−3)−(1)(1))−1((1)(−3)−(1)(1))+1((1)(1)−(−3)(1)) =−24+4+4=−16$$
Kofaktor:
$$C14​=(−)(16)=−16$$
Kontribusi:
$$1⋅(−16)=−16$$

### c. Elemen a13= 1
Minor:
$$
M_{13} =
\begin{vmatrix}
-3 & 1 & 1 \\
1 & 1 & 1 \\
1 & 1 & -3
\end{vmatrix}
= -3
\begin{vmatrix}
1 & 1 \\
1 & -3
\end{vmatrix}
- 1
\begin{vmatrix}
1 & 1 \\
1 & -3
\end{vmatrix}
+ 1
\begin{vmatrix}
1 & 1 \\
1 & 1
\end{vmatrix}
$$
Hitung (Sarrus):
$$=(−3)(1(−3)−1⋅1)−1(1(−3)−1⋅1)+1(1⋅1−1⋅1) =12+4+0=16 $$
Kofaktor:
$$C13​=(+)16$$
Kontribusi:
$$1⋅16=16$$

### d. Elemen a14= 1
Minor: $$
M_{14} =
\begin{vmatrix}
-3 & 1 & 1 \\
1 & 1 & -3 \\
1 & 1 & 1
\end{vmatrix}
= -3
\begin{vmatrix}
1 & -3 \\
1 & 1
\end{vmatrix}
- 1
\begin{vmatrix}
1 & -3 \\
1 & 1
\end{vmatrix}
+ 1
\begin{vmatrix}
1 & 1 \\
1 & 1
\end{vmatrix}
$$
Hitung (Sarrus):
$$=(−3)(1⋅1−(−3)⋅1)−1(1⋅1−(−3)⋅1)+1(1⋅1−1⋅1)=−12−4+0=−16$$
Kofaktor:
$$C14​=(−1)1+4(−16)=(−1)5(−16)=16$$
Kontribusi:
$$1⋅16=16$$

## Rumus utama
$$
A^{-1} = \frac{1}{\det(A)} \, \text{adj}(A)
$$

$$
(\text{adj}\, A)_{ij} = (-1)^{i+j} \, M_{ji}
$$

## 4. Matriks 2×2
Determinan: 
$$det(A)=(−7)(4)−(−5)(1)=−28+5=−23$$
Minor:
$$M11​=4,M12​=1,M21​=−5,M22​=−7$$
Kofaktor:
$$C14​=(−1)1+4(−16)=(−1)5(−16)=16$$
Adjoint (transpose kofaktor): $$adj(A)=[4−1​5−7​]$$
Invers: $$
A^{-1} = -\frac{1}{23}
\begin{bmatrix}
4 & -1 \\
5 & -7
\end{bmatrix}
=
\begin{bmatrix}
-\frac{4}{23} & \frac{1}{23} \\
-\frac{5}{23} & \frac{7}{23}
\end{bmatrix}
$$

## 5. Matriks 3×3
Diketahui Determinan:

$$
\det(A) = -2
$$

Minor:

$M_{11}$:

$$
M_{11} =
\begin{vmatrix}
-2 & -1 \\
0 & 1
\end{vmatrix}
$$

$$
= (-2)(1) - (-1)(0)
$$

$$
= -2 - 0 = -2
$$

$M_{12}$:

$$
M_{12} =
\begin{vmatrix}
1 & -1 \\
0 & 1
\end{vmatrix}
$$

$$
= (1)(1) - (-1)(0)
$$

$$
= 1 - 0 = 1
$$

$M_{13}$:

$$
M_{13} =
\begin{vmatrix}
1 & -2 \\
0 & 0
\end{vmatrix}
$$

$$
= (1)(0) - (-2)(0)
$$

$$
= 0 - 0 = 0
$$

$M_{21}$:

$$
M_{21} =
\begin{vmatrix}
2 & -3 \\
0 & 1
\end{vmatrix}
$$

$$
= (2)(1) - (-3)(0)
$$

$$
= 2 - 0 = 2
$$

$M_{22}$:

$$
M_{22} =
\begin{vmatrix}
0 & -3 \\
0 & 1
\end{vmatrix}
$$

$$
= (0)(1) - (-3)(0)
$$

$$
= 0 - 0 = 0
$$

$M_{23}$:

$$
M_{23} =
\begin{vmatrix}
0 & 2 \\
0 & 0
\end{vmatrix}
$$

$$
= (0)(0) - (2)(0)
$$

$$
= 0 - 0 = 0
$$

$M_{31}$:

$$
M_{31} =
\begin{vmatrix}
2 & -3 \\
-2 & -1
\end{vmatrix}
$$

$$
= (2)(-1) - (-3)(-2)
$$

$$
= -2 - 6 = -8
$$

$M_{32}$:

$$
M_{32} =
\begin{vmatrix}
0 & -3 \\
1 & -1
\end{vmatrix}
$$

$$
= (0)(-1) - (-3)(1)
$$

$$
= 0 + 3 = 3
$$

$M_{33}$:

$$
M_{33} =
\begin{vmatrix}
0 & 2 \\
1 & -2
\end{vmatrix}
$$

$$
= (0)(-2) - (2)(1)
$$

$$
= 0 - 2 = -2
$$

Kofaktor:

$$
C_{ij} = (-1)^{i+j} M_{ij}
$$

$$
C =
\begin{bmatrix}
-2 & -1 & 0 \\
-2 & 0 & 0 \\
-8 & -3 & -2
\end{bmatrix}
$$

Adjoin (Transpose kofaktor):

$$
\operatorname{adj}(A) =
\begin{bmatrix}
-2 & -2 & -8 \\
-1 & 0 & -3 \\
0 & 0 & -2
\end{bmatrix}
$$

Invers:

$$
A^{-1} = \frac{1}{\det(A)} \operatorname{adj}(A)
$$

$$
A^{-1} = \frac{1}{-2}
\begin{bmatrix}
-2 & -2 & -8 \\
-1 & 0 & -3 \\
0 & 0 & -2
\end{bmatrix}
$$

Hasil Akhir:

$$
A^{-1} =
\begin{bmatrix}
1 & 1 & 4 \\
\frac{1}{2} & 0 & \frac{3}{2} \\
0 & 0 & 1
\end{bmatrix}
$$

## 6. Matriks 4×4
Determinan: det(A)=−80
Minor: \[
A =
\begin{bmatrix}
1 & -3 & 1 & 1 \\
-3 & 1 & 1 & 1 \\
1 & 1 & -3 & 1 \\
1 & 1 & 1 & -3
\end{bmatrix}
\]
kofaktor: $$\[
C =
\begin{bmatrix}
16 & 16 & 16 & 16 \\
16 & 16 & 16 & 16 \\
16 & 16 & 16 & 16 \\
16 & 16 & 16 & 16
\end{bmatrix}
\]$$
Adjoint (transpose kofaktor): $$adj(A)=CT=C$$
Invers: Tidak ada