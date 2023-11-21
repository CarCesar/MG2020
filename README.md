# Eleições Municipais 2020

Uma visualização das prefeituras por partidos no estado de Minas Gerais

Para acessar ao  [Mapa, clique aqui](https://carcesar.github.io/MG2020/).

## Motivações
Após as eleições municipais de 2020, tive algumas curiosidades, entre elas:
- ver como se dispunha os partidos, se alguma região seria governada por um mesmo partido?
- ver a qual partido iria governar mais prefeituras.
- ver a população que iria ser governada por cada partido.

## Fonte de dados
Para esse trabalho, foram utilizados dados do TSE, IBGE e logos coletados dos partidos politicos.

## Desenvolvimento
O trabalho foi desenvolvido em Python, e as vis foram criadas e interligadas com a biblioteca Altair.

## Descrição
![image](https://github.com/CarCesar/MG2020/assets/73307575/46ab2d49-1746-4696-921a-c4fb22b1cac4)

A viz é formada por um mapa de minas com a coloração dos partidos(não foi a melhor escolha de cores possível).

Logo a direita tem um gráfico de partidos por porcentagem da população que votou no prefeito eleito, sendo que o triângulo verde indica o prefeito de cada partido que teve maior aprovação da população, enquanto o vermelho indica a menor aprovação, já a estrela amarela indica a média.

Abaixo desse gráfico, se encontra 2 gráficos de barras interligados que representam a quantidade de prefeituras que cada prefeitura governa e a população governada, pela alta divemensão, os graficos seguem escala sqrt e log, respectivamente.

Essa vis possui interatividade, ao escolher um partido em qualquer gráfico, ele será evidenciado em todos os outros.

## Possíveis melhorias

Como já mencionado, a coloração não foi escolhida da melhor maneira possível, existiriam maneiras melhores, uma dessas maneiras seria por espectro político, porém após conversar com historiadores e outros pesquisadores mas envolvidos, cheguei na conclusão de que não seria uma coisa tão fácil, mas é um desejo futuro. 


