# sisop_2015_2_t1
Trabalho 1 de SO 2015/2 -- façam fork desse repositório e o tornem privado.

## Descrição 

O trabalho 1 consiste em desenvolver um programa paralelo em pThreads e C/C++ que execute em Linux e resolva o problema de contagem de ocorrências de uma string em um arquivo de texto, incluindo ocorrências na mesma linha. 

Uma thread deverá ser criada para ler o arquivo para um buffer, enquanto outras threads devem ser criadas para fazer a busca pela string. O resultado final será um número impresso na stdio (nada mais deverá ser impresso na stdio no código final a ser testado).

## Restrições

- O programa deverá ser feito em pThreads e C ou C++ e executar em Linux sem precisar de bibliotecas adicionais;
- Uma thread de processamento deverá ser criada para cada processador/core disponível no computador;
- O paralelismo deve ser aproveitado (ou seja, vários cores -- melhor desempenho);
- O repositório deve ser privado;
- O programa deverá ter apenas um parâmetro -- o nome do arquivo a ser analisado;
- O trabalho pode ser feito em duplas.

## Material a ser entregue

- Makefile que gere um executável <psearch>;
- README.md descrevendo a implementação, como os problemas de paralelização e sincronização foram resolvidos, ambiente onde experimentos foram executados e apresentando resultados de tempo de execução e speedup para um número razoável de execuções; 
- Link para Google Drive com os casos de teste usados e os resultados esperados (acessível pelo professor);
- Código fonte comentado;
- E o próprio repositório com commits que façam sentido.

## Data de entrega 

- Repositórios devem ser atualizados até dia *30/09*
- Apresentação no dia *01/10* em aula

## Referências

- POSIX Threads Programming https://computing.llnl.gov/tutorials/pthreads/
- Linux POSIX Threads http://www.yolinux.com/TUTORIALS/LinuxTutorialPosixThreads.html
