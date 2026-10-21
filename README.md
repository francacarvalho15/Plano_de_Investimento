# Plano_de_Investimento
Projeto de Plano de Investimentos - DIO - Ferramenta de Controle de Investimentos com Excel

A ferramenta, nada mais é, do que uma simulação de como seria o investimento em certos produtos e o quanto seria o total investido no decorrer dos anos.

Na tabela de Configurações, temos o salário do investidor, o rendimento da carteira, e o valor sugerido a ser investido
Em seguida, temos o Investimento Mensal, onde mostra a simulação de quanto seria o investimento no decorrer dos anos.
Os Anos Investidos, a Quantidade Investida e a Taxa de Rendimento, estão brancas, portanto, são alteráveis, enquanto o Patrimônio Acumulado e Dividendos Mensais, são células bloqueadas para edição, deixando na coloração cinza para diferenciar das outras.
Em Patrimônio Acumulado, foi utilizado a fórmula VF, para que seja feito o cálculo automático após a alteração das células em branco, já em Dividendos Mensais, é feita a multiplicação do Patrimônio e a Taxa de Rendimento, onde nomeei cada uma para que possa ser mais fácil se localizar na planilha, no final desta explicação, deixarei o nome de cada célula que alterei no decorrer da aula.

Em Cenários, temos outros exemplos de quanto seria o patrimônio em outra quantidade de X anos.
Onde mostra o Patrimônio, foi novamente utilizado VF, para que seja feita alteração automática, em Dividendo, é feito o cálculo do patrimônio dessa mesma tabela, com a taxa de rendimento da tabela anterior.
Deixei as células cinzas também, indicando que são valores inválidos para edição.

Logo abaixo temos o perfil do investidor, separados por;
Conservador, Moderado e Agressivo.
O valor investido no mês, mostra o valor do investimento, onde nomeei como "aborte" na tabela de Investimento Mensal, para que seja mais fácil procurar, e utilizar na tabela seguinte.

Temos os tipos de FII, que são os produtos a serem investidos, o percentual sugerido, indicando a porcentagem a ser investida no produto, e os valores, que são os valores investidos de acordo com a porcentagem.

Em Percentual Sugerido, utilizei o PROCV, em uma tabela de apoio, presente na mesma planilha, para automatizar o cálculo, após mudar o perfil do investidor que se encontra acima.

Abaixo, mostra o gráfico dos investimentos, onde utilizei como base, a própria tabela onde mostra o percentual sugerido, que também se altera após mudar o perfil do investidor.

Células nomeadas;

Tabela de Configurações
D15 = salario
D16 = Rendimento
D17 = sugestaoInvest

Tabela de Investimento Mensal
D20 = investimento
D21 = qtdAnos
D22 = taxaMensal
D23 = patrimonio

