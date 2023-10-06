# SistemasOperacionais_GA
## OBJETIVO
Desenvolvimento dos conceitos adquiridos na disciplina de Laboratório de Sistemas Operacionais, tais como programação shell script, processos, threads e paradigma produtor/consumidor. Além disso, estimular a desenvoltura e apresentação oral do aluno.

## METODOLOGIA
O trabalho deve ser realizado de forma individual, utilizando qualquer linguagem. A apresentação deve ser realizada no dia 06/10/2023, com duração de 10 minutos. A nota deste trabalho faz parte do GA.

## DEFINIÇÃO
O Kubernets é um orquestrador de PODs. Resumidamente, o Kubernets possui um nodo Master que possui um escalonador para alocar os PODs de aplicações em diferentes nodos, chamados Workers. O escalonador do Kubernets leva em consideração apenas a quantidade de CPU e memória dos Workers para alocar os PODs. O aluno deve projetar uma solução que cria um nodo Master e no mínimo dois nodos Workers para escalonar PODs, considerando outras métricas de alocação, por exemplo, espaço em disco, latência da rede entre Works. Posteriormente, deve se criar uma quantidade significativa de PODs (mais que uma dezena) com diferentes capacidades computacionais e alocar esses PODs nos nodos Workers, seguindo um algoritmo de escalonamento com no mínimo três métricas de alocação, i.e., uma a mais que a opção padrão do Kubernets. Finalmente, a solução deve mostrar onde os PODs estão alocados e os recursos computacionais disponíveis e ocupados em cada Workers. A figura abaixo representa a ideia básica do trabalho a ser desenvolvido.

![image](https://github.com/claraburghardt/SistemasOperacionais_GA/assets/85072411/4e99acd9-fbfa-4bd5-9230-bb056d42cd76)

O aluno deve escolher as técnicas que irão utilizar no trabalho, por exemplo utilizar, sigle thread, multithreads, paradigma produtor/consumidor, etc. A implementação pode ser realizada em simulação ou na própria ferramenta kubernets. 
