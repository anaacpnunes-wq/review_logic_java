# entrada e saída de dados (I/O) em JAVA. 

> basicamnete é a forma com seu programa recebe **informações (entrada)** e como ele mostra as informações **(saída)**. 

---

## 1. Saída: 

O objeto **System.out** representa a saída padrão, permitindo exibir dados no console quando executamos um aplicativo em Java. O System.out possui diversos métodos para gerar saídas, sendo os mais utilizados os métodos **println**, **printf** e **print**.  

para emojis apertar windons + .

## ✅ Método println()

O método System.out.println() gera uma string de texto, cria uma nova linha abaixo da atual e então posiciona o cursor nesta linha.

**exemplos:**

```
System.out.println("O grêmio vai ser campeão");
System.out.println("meu segundo println em java");
```
## ✅ Método printf()

O método System.out.printf() mostra os dados da saída formatados. Um especificamente em formato se inicia com o simbolo %, seguido por um caractereque representa o tipo de dado. 

**exemplos:**

```
Double numDecimal = 23.8954;
int minhaIdade = 17;
string meuNome = "carol";
char nome = 'C';

Sistem.out.printf("numero = % . 2f%n" , numDecimal)
System.out.printf("minha idade = % . 2s%n" , minhaIdade);
System.out.printf("meu nome = % . 2s%n" , meuNome); 
System.out.printf("primeira letra = %C" , carol);
```

