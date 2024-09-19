# Make
Make é um comando específico do CS50 que resume o comando seguinte e em resumo compila o arquivo.c que o usuário especificou como argumento.

# Clang
Clang é um comando para compilar e aceita vários comandos para formatar nome do arquivo e para linkar as bibliotecas tipo <cs50.h> e <stdio.h>.

# Argc e Argv[]
Argc é um contador de argumentos ao executar o programa e Argv[] é uma matriz que aceita valores string que contém todos os argumentos inseridos no terminal ao executar o programa.
```C
#include <stdio.h>
#include <cs50.h>

int main(int argc, string argv[])
{
	if (argc != 2) // checkup pra saber se o usuário está inserindo o número de argumentos corretamente.
	{
		printf("Uso correto: ./nome_programa argumento\n")
		return 1; // número de erro que retorna secretamente para o computador, você como programador pode inserir qualquer número pra associar a um erro.
	}
	else
	{
		printf("O segundo argumento é %s\n",argv[1]); 
		// index 1 para acessar o segundo valor.
		return 0;
		// valor de retorno para programas que representa "Tudo correu bem!"
	}
}
```
Uso correto do programa que acabamos de escrever, este argumento pode ser qualquer valor que queiramos usar porém teremos que converter caso tenha a necessidade de outro tipo de valor (int , float , double).
```shell
./nome_programa argumento
```

