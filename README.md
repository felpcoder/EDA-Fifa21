# EDA-Fifa21

O objetivo principal é fazer uma análise exploratória de dados, usando o dataset 'FIFA21_official_data.csv' disponível no kaggle. O projeto ainda está em andamento e em breve será feita uma visualização de dados no PowerBI.

https://www.kaggle.com/bryanb/fifa-player-stats-database

Será utilizada a linguagem Python e principalmente as bibliotecas numpy e pandas.

# O dataset

O dataset 'FIFA21_official_data.csv' é um banco de dados do jogo FIFA 21, que é um videogame de simulação de futebol desenvolvido e publicado pela Electronic Arts. Este banco de dados, possuí informações, acerca dos jogadores, dispostas em 65 colunas. 

A seguir temos todas as colunas do dataset e algumas estão comentadas:

 'ID', número associado a cada jogador <br>
 'Name', nome de cada jogador<br>
 'Age', idade de cada jogador<br>
 'Photo', foto de cada jogador<br>
 'Nationality', nacionalidade de cada jogador<br>
 'Flag', bandeira associada a nacionalidade de cada jogador<br>
 'Overall', nível de habilidade padrão medido de 0 a 100 de cada jogador. É composto pelas demais métricas associadas a demais colunas do dataset. Note que quanto melhor um jogador mais alto é o seu overall.  <br>
 'Potential', simboliza a maior expectativa sobre como o overall do jogador vai evoluir, assim quanto mais novo um jogador mais potencial de melhorar o seu overall ele tem, 'Potential' seria a possibilidade máxima de crescimento.<br>
 'Club', time de cada jogador.<br>
 'Club Logo', foto do time associado ao jogador.<br>
 'Value', valor de mercado do jogador, é cotado em euros.<br>
 'Wage', salário do jogador, é cotado em euros.<br>
 'Preferred Foot', pé preferido do jogador.<br>
 'International Reputation',<br>
 'Weak Foot', habilidade com o pé que não é o preferido do jogador, medido de 0 a 5, onde 0 representa a mais baixa habilidade.<br>
 'Skill Moves', de 0 a 5 a facilidade que o jogador tem para fazer movimentos especiais no jogo. 0 representa a maior dificuldade<br>
 'Work Rate',<br>
 'Body Type',<br>
 'Real Face',<br>
 'Position', posição em que cada jogador é escalado por default.<br>
 'Jersey Number',<br>
 'Joined', data que o jogador foi contratado por determinado clube.<br>
 'Loaned From', <br>
 'Contract Valid Until', validade do contrato de cada jogador.<br>
 'Height',<br>
 'Weight',<br>
 'Best Position', melhor posição em que cada jogador pode ser escalado.<br>
 'Best Overall Rating', no Fifa existem várias versões do Overall dos jogadores através de cartas comemorativas. Essa coluna informa o Overall mais alto que aparece dentre as cartas dos jogadores. Cartas são versões comemorativas dos jogadores que são usadas em um dos modos do jogo.<br>
 'Release Clause', valor da clausula de quebra de contrato de cada jogador, é cotada em euros. <br>
 'DefensiveAwareness'<br>
 <br>
A seguir, todas as colunas representam o nível de habilidade do jogador, que são medidas de 0 a 100 onde 100 representa o máximo de habilidade possível e 0 sem habilidade nenhuma, para fazer a ação determinada pelo nome da coluna. Assim, quanto maior o valor do jogador em 'Crossing', melhor o jogador efetuará cruzamentos no jogo. <br>
<br>
 'Crossing',<br>
 'Finishing',<br>
 'HeadingAccuracy',<br>
 'ShortPassing',<br>
 'Volleys',<br>
 'Dribbling',<br>
 'Curve',<br>
 'FKAccuracy',<br>
 'LongPassing',<br>
 'BallControl',<br>
 'Acceleration',<br>
 'SprintSpeed',<br>
 'Agility',<br>
 'Reactions',<br>
 'Balance',<br>
 'ShotPower',<br>
 'Jumping',<br>
 'Stamina',<br>
 'Strength',<br>
 'LongShots',<br>
 'Aggression',<br>
 'Interceptions',<br>
 'Positioning',<br>
 'Vision',<br>
 'Penalties',<br>
 'Composure',<br>
 'Marking',<br>
 'StandingTackle',<br>
 'SlidingTackle',<br>
 'GKDiving',<br>
 'GKHandling',<br>
 'GKKicking',<br>
 'GKPositioning',<br>
 'GKReflexes',<br>
