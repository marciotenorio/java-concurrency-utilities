# Trabalho Prático Programação Concorrente: Java Concurrency Utilities

### Disciplina: Programação Concorrente - IMD/UFRN
### Prof. Dr. Everton Ranielly De Sousa Cavalcante
#### Discentes: Márcio Tenório Júnior e Roberto Manaia dos Santos Junior

### Descrição
A tarefa central a ser realizada neste trabalho consiste em projetar e implementar uma solução concorrente para o cálculo do número e mediante uma série infinita utilizando threads independentes/concorrentes aproveitando das abastrações fornecidas pelo Java como Executors, ExecutorService, etc e utilizando as abordagens ``fixed``, ``cached`` e ``work stealing`` thread pools.

### Arguments:  
To fixed pool: -f poolSize numberOfTerms

> -f 10 10

To cached: -c numberOfTerms
> -c 15

To work stealing: -ws numberOfTerms

> -ws 20
