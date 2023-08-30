# Ativ Programação - Memória Compartilhada
Repositório para atividade de programação memória compartilhada entre processos

## Memória Compartilhada

Crie um código-fonte que utilize fork() e shmget() entre 2 processos (pai e filho). Seu código deve garantir que:

* o processo pai e o processo filho compartilhem uma variável simples (por exemplo, inteiro - valor 1)
* processo pai imprime o valor inicial dessa variável; em seguida, cria o processo filho e espera-o
* o processo filho acessa esta variável, realiza uma operação (por exemplo, adição - valor 2, totalizando 3), modificando o valor; em seguida, o processo filho termina
* o processo pai realiza uma outra operação (por exemplo, multiplicação - valor 4, totalizando 12), modificando novamente o valor, e imprime novamente a variável

Essa lógica de execução deve ser garantida no seu código-fonte em C.

**Trabalho individual.**

Você deve submeter:

- o código fonte do seu programa em C (coloque seu nome e TIA no início do código fonte)
- um PDF com prints de tela mostrando a execução do código.
