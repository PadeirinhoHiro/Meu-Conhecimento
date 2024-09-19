C é uma linguagem de alto nível (comparada com assembly ou binário), porém também de baixo nível (quando comparada com python ou javascript). C não contém estruturas de dados pré-configuradas e deixa a cargo do programador estrutura-las, além disso C é uma linguagem fortemente tipada em que pra declarar variáveis e funções você precisa definir o tipo da variável para variáveis e tipos de retorno e de argumentos para funções!

Abaixo um código para printar Hello World! no terminal
```C
#include <stdio.h>

int main(void)
{
	printf("Hello World!\n")
}
```
OBS: \\n não é obrigatório, porém se não for utilizado no printf final do programa o input do terminal se "cola" no ultimo caractere da string.
```shell
Hello World!$
```
Representação quase fiel de um printf  sem \\n
OBS: $ é onde você irá ver os comandos do terminal que você irá escrever.

# Links úteis para saber mais sobre esta linguagem!

[[Tipos de Dados]]
[[Condicionais]]
[[Loops]]
[[Array]]
[[Compilação]]
[[Comandos de Terminal]]

