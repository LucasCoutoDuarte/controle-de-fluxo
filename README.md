🚀 Desafio Controle de Fluxo - DiO

Este projeto é uma implementação do desafio proposto na plataforma Digital Innovation One (DIO), abordando conceitos de controle de fluxo em Java.

📌 Descrição do Desafio

O sistema recebe dois parâmetros via entrada do usuário e realiza uma contagem iterativa (usando um loop for), exibindo no console os números incrementados.

⚙️ Regras do Desafio:

Se o primeiro número for maior que o segundo, uma exceção personalizada ParametrosInvalidosException será lançada.

Caso contrário, o programa imprimirá a sequência de números entre os dois valores fornecidos.

🛠 Tecnologias Utilizadas

Java 8+

Scanner para entrada de dados

Tratamento de Exceções

📂 Estrutura do Projeto

O projeto contém as seguintes classes:

Contador.java: Classe principal contendo a lógica do programa.

ParametrosInvalidosException.java: Classe que representa a exceção personalizada.

▶️ Como Executar

Clone o repositório ou copie os arquivos.

Compile o código com javac Contador.java.

Execute o programa com java Contador.

Insira os valores conforme solicitado pelo terminal.

💻 Exemplo de Entrada e Saída

Entrada:

Digite o primeiro parâmetro:
5
Digite o segundo parâmetro:
10

Saída:

Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5

Se o primeiro parâmetro for maior que o segundo:

O segundo parâmetro deve ser maior que o primeiro