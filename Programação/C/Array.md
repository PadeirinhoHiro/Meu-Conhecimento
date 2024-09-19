Arrays são estruturas de dados que guardam dados sequencialmente na memória em uma variável matriz, de uma forma mais simples são matrizes que conseguem comportar valores de tipos iguais (pelo menos com meu conhecimento até agora).
```C
int matriz[2];
matriz[0] = 2;
matriz[1] = 3;
```

Arrays também podem ser escritas de forma N-dimensional
```C
int matriz_2[2][2];
matriz_2[0][0] = 1;
matriz_2[0][1] = 2;
matriz_2[1][0] = 3;
matriz_2[1][1] = 4;
```
$$
\begin{bmatrix}
\begin{bmatrix}
1\\2
\end{bmatrix}
\begin{bmatrix}
3\\4
\end{bmatrix}
\end{bmatrix}
$$
Visualização da matriz bidimensional.

OBS:
Strings em C são arrays de Char (caracteres)
```C
char string[4];
string[0] = 'H'
string[1] = 'O'
string[2] = 'L'
string[3] = 'A'

// se caso houvesse um printf("%c%c%c%c",string[0]....)
// o output seria HOLA
```
