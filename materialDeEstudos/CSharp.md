# *Sintax principal*
````csharp
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
````
# Atalhos:

| Atalho      | O que faz?                                                  |
| ----------- | ----------------------------------------------------------- |
| Control + . | serve para abrir o menu de **Ações Rápidas e Refatorações** |
| cw          | sigla para o Control.WriteLine()                            |
# variável:
sintase: tipo nome = valor(não precisa escrever o valor agora)
```
//Sem valor:
int speed;(; serve para pular)

//com valor:
int speed = valor; 

//se eu usar tipo float tem que colocar um f depois para indicar que é um float:
int speed = 3.5f;

//string entre aspas:
int enemyName = "nome do personagem";
```
# Funções/metódos:
```
if (condicao) { // Código executado se a condição for verdadeira }

Ex:
if (nota >= 7)
{
    Console.WriteLine("Aprovado");
}
else if (nota >= 5)
{
    Console.WriteLine("Recuperação");
}
else
{
    Console.WriteLine("Reprovado");
}

```
# Arrays/listas:
```
sintase: nome da variável(tipo) [] nome; para já passar os valores adicione = new int[] {valores por vírgula}

int[] inArray = new int[] {};
```
# Laços de repetição:
```
sintaxe: for(declaração condicional- início; condição; atualização) 
for (int i =0 < intArray.Length; i++)
{
}
```
