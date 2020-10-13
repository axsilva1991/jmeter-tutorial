# jmeter-tutorial

### Modelando o cenário de testes de performance
é interessante capturar os valores como:

Funcionalidades ?
	Quais são as funcionalidades mais criticas ?
	Quais serão as mais acessadas ?

Critérios de aceite ?
	Carga Qual será?
	Tempo de resposta
	Percentual de falhas
  
Outro item interessante é colocar a configuração de execução para auxiliar é importante saber como calcular a quantidade de usuários virtuais.

### Como calcular a quantidade de usuários virtuais
VU = RPS * TEF
por exemplo RPS = 40 TPS
TEF = 0.5 seg
Legenda:
TEF = Tempo estimado de resposta
VU = Virtual User
RPS = Requisições por segundo

### Rampa de acessos.
é sempre importante deixar a rampa de acessos bem distribuida, pois é interessante ver o autoscalle dos pods de forma fluida.

### Recomendações para execução de testes de performance:
* Reiniciar a Maquina para liberar espaço da memoria.
* Fechar os outros programas.
* Utilizar menos recursos do jmeeter, por exemplo: arvore de resultados.
* Veririficar se o servidor de aplicação está dedicado para o teste, para que os resultados não sejam destorcidos.

