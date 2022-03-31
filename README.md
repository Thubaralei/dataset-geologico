# Aplicacao-machine-learning-em-dataset-geologico
Repositorio publico de algoritimos para um mecanismo de validação de dados geologicos em geral, utilizaremos formulação de dataset em sql e tratamento de dados utilizando python


Localizado no Norte do Estado de Santa Catarina, o Folhelho Lontras, é um reconhecido depósito fossilífero do Pennsilvaniano, com biota diversa e bem preservada (esponjas, peixes, ammonóides, insetos, madeiras e muitos outros; Figura 1) que inclui preservação de tecidos duros e / ou moles. Nos últimos 20 anos, esse intervalo tem sido intensamente estudado (HFFL, Fm. Campo Mourão, Grupo Itararé, Bacia do Paraná). Foi descoberto em 1908 por Jay Markus Woodworth e Euzébio Paulo de Oliveira em sua procura por depósitos glaciais na porção sul da Bacia do Paraná (Mouro et al., 2018), o que permitiu assinalar a presença de uma baía de paleofjord marinho restrita com períodos prolongados de anoxia / euxinia do fundo do mar e euxinia intermitente na zona fótica. Apesar dos robustos dados, dúvidas referente:  a metodologia de coleta, visto que os níveis (1-4) e subníveis correspondentes (1A-D, 2A-B, 3A-D, 4A) compartilham a semelhante litologia, mas não a mesma espessura; e como existiu uma enorme presença de vida em um ambiente disóxico-anóxico? Permaneceram em aberto. Dessa forma, este trabalho de conclusão de curso se volta a simulação numérica como proxy para validar o conjunto de dados da pesquisa de paleoecologia na Lontras Shale Lagerstatte (LSL). Será feito o uso de simulações estatística usando Python, mais especificamente as funcionalidades do Panda e Skitlearning, formulando um Dataset funcional para aplicação de técnicas de Machine Learning. Essas funcionalidades permitem simular centenas de variações de dados, podendo ser replicado em situações semelhantes e facilmente adaptado para leituras robustas. Apesar das informações confiáveis obtidas, poucas questões que permaneceram em aberto, este projeto tem como propósito, via simulação numérica, levantar dados para a validação, com intuito de ratificar a presença de vida em ambiente disóxico-anóxico e levantar discussões sobre processos e paleoambientes, visando auxiliar no entendimento da paleoecologia.


4 – OBJETIVOS 

4.1. Principal
Determinar os possíveis ciclos paleoecologicos por uma simulação numérica estatística. Analisar a distribuição dos dados nas análises e amostragens do método multiproxy usando dados paleontológicos, palinológicos, geoquímicos e paleométricos. Montagem de dataset para reconhecimento de padrões numéricos processados por aprendizado de máquina utilizando bibliotecas python.

4.2. Específicos
Modelagem de dados utilizando aprendizado de máquina, para validação de dados paleoecologicos. As técnicas de aprendizado de máquina e ciência de dados, nos proporciona uma ampla gama de ferramentas capazes de manipular e processar dados numéricos.  Modelagem de uma arvore de decisões capaz de predizer valores de amostra para validação, com uma interface acessível para um usuário inexperiente em Python.

6 – MATERIAIS E MÉTODOS 
            As atividades que serão desenvolvidas neste projeto se resumem a levantamento bibliográfico a respeito da temática de desenvolvimento da vida em ambiente anoxicos e as ferramentas de aprendizado de máquina. Também serão realizados a formulação de um Dataset funcional, um mecanismo de predição de dados e modelos gráficos interpretativos dos resultados simulados.

Levantamento Bibliográfico: As bibliografias que servirão como base para este trabalho são monografias, dissertações, teses, artigos científicos e livros que abordam processamento de Dataset’s utilizando aprendizado de máquina em bibliotecas Python na plataforma Jupyter. Além disso, será realizada uma pesquisa na literatura sobre desenvolvimento da vida em ambientes anoxicos, por fim de encontrar dados e informações pertinentes para enriquecer o Dataset formado pela amostra do CAMPALEO.

Formulação do Dataset, aprendizado de máquina e modelo de previsão: Serão confeccionados Dataset de dados reais e possíveis informações coringas para enriquecer o número de dados e deixar modelos mais robustos (Figura 2 - 3). O objetivo será fazer tabelamento de dados numerosos o suficiente para rodar um modelo de árvore de decisões capaz de predizer valores com base nos já existes da amostragem, criando amostras sintéticas capazes de validar valores reais. Também será confeccionado uma interface semelhante a um dashbord para trabalho no tipo de modelo. 

.
Amostra	Nível	MOA-NF	OP-AL	OP-EQUI	N.OP-N.BIO	SPONG	ESPORO	PÓLEN	PRASINÓFITAS

FL 1	102	29	4	2	60	0	1	0	4

FL 2	97,5	27	10	3	50	0	0	4	6

FL 3	92,5	62	3	1	33	0	0	0	1

FL 4	87	54	7	4	21	1	0	0	13

FL 5	81	70	3	1	18	0	0	0	8

FL 6	76,5	64	1	0	29	0	0	0	6

FL 7	72	71	2	0	24	0	0	0	3

FL 8	65,5	78	4	1	15	0	0	0	2

FL 9	58	74	3	0	20	0	0	0	3

FL 10	50	62	4	0	30	0	0	0	4

FL 11	42	75	2	0	21	1	0	0	1

FL 12	35	89	1	0	8	0	0	0	2

FL 13	29,5	84	0	0	12	0	0	0	4

FL 14	23	89	1	0	9	0	0	0	1

FL 15	16,5	79	0	0	18	0	0	1	2

FL 16	11	72	1	0	16	0	0	1	10

FL 17	6	71	2	0	19	0	0	0	8


Análises Micropaleontológicas e Geoquímicas: Não serão realizadas novas análises químicas, e micropaleontologicas por vez que serão usados dados pré-existentes. O tratamento de dados cedidos pela literatura será feito através dos softwares Excel, Jupyter, R, GitHUB (Figura 4). Serão elaborados gráficos e diagramas expositivos dos modelos de predição e aprendizado de máquina, como os diagramas desenvolvidos através de bibliotecas estatísticas em Python. 

Árvore de decisões e Inteligência artificial, interface de usuário: As bibliotecas Python, deverão ser compostas de diversos scripts e um Dataset fixo para processamento (Figura 5). Novas versões do Dataset serão geradas assim que as primeiras predições forem feitas, fomentando um banco de dados funcional para aprendizado dos mecanismos de inteligência artificial. Uma interface de acesso da predição com facilitadores de usuário para poder montar manualmente as correlações identificadas. Será feito também um apanhado da bibliografia estatística por trás das bibliotecas Skitlearning usadas para a predição, e das interfaces CSS para usuário. 

 


Integração e Interpretação dos dados: A última etapa do trabalho consistirá na compilação e integração de todos os dados adquiridos ao longo do todo o projeto de conclusão de curso. O objetivo desta etapa será a elucidação das questões que motivaram a pesquisa, bem como das dúvidas que surgirão ao longo do projeto, discutindo os resultados com aqueles já publicados nos trabalhos anteriores sobre os depósitos do folhelho lontras e o surgimento de vida em ambiente anoxico.
