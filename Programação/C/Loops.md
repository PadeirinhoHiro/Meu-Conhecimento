## For
```C
for (int i = 0; i < 10; i++) // inicia i em 0 e roda o código e repete até i ser igual a 10!
{
	printf("i é agora: %i\n",i)
}
```

## While
```C
int i = 0;
while (i < 12) // vai rodar enquanto (while) i for menor que 12
{
	printf("i é agora: %i\n",i)
	i++
}
```

## Do  e While
```C
int i;
do // vai rodar pelo menos uma vez e depois vai seguir a mesma lógica do while normal!
{
	printf("Insira 0 para sair do programa\n");
	scanf("%i",&i);
}
while (i != 0);
```