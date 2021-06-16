# EDA-Fifa21

O objetivo principal é fazer uma análise exploratória de dados, usando o dataset 'FIFA21_official_data.csv' disponível no kaggle. 

https://www.kaggle.com/bryanb/fifa-player-stats-database

Será utilizada a linguagem Python e principalmente as bibliotecas numpy e pandas.

# O dataset

O dataset 'FIFA21_official_data.csv' é um banco de dados do jogo FIFA 21, que é um videogame de simulação de futebol desenvolvido e publicado pela Electronic Arts. Este banco de dados, possuí informações, acerca dos jogadores, dispostas em 65 colunas. 

A seguir vamos comentar algumas colunas:

 'ID', número associado a cada jogador
 'Name', nome de cada jogador
 'Age', idade de cada jogador
 'Photo', foto de cada jogador
 'Nationality', nacionalidade de cada jogador
 'Flag', bandeira associada a nacionalidade de cada jogador
 'Overall', nível de habilidade padrão medido de 0 a 100 de cada jogador. É composto pelas demais métricas associadas a demais colunas do dataset. Note que quanto melhor um jogador mais alto é o seu overall.  
 'Potential', simboliza a maior expectativa sobre como o overall do jogador vai evoluir, assim quanto mais novo um jogador mais potencial de melhorar o seu overall ele tem, 'Potential' seria a possibilidade máxima de crescimento.
 'Club', time de cada jogador.
 'Club Logo', foto do time associado ao jogador.
 'Value', valor de mercado do jogador, é cotado em euros.
 'Wage', salário do jogador, é cotado em euros.
 'Preferred Foot', pé preferido do jogador.
 'International Reputation',
 'Weak Foot', habilidade com o pé que não é o preferido do jogador, medido de 0 a 5, onde 0 representa a mais baixa habilidade.
 'Skill Moves', de 0 a 5 a facilidade que o jogador tem para fazer movimentos especiais no jogo. 0 representa a maior dificuldade
 'Work Rate',
 'Body Type',
 'Real Face',
 'Position', posição em que cada jogador é escalado por default.
 'Jersey Number',
 'Joined', data que o jogador foi contratado por determinado clube.
 'Loaned From', 
 'Contract Valid Until', validade do contrato de cada jogador.
 'Height',
 'Weight',
 'Best Position', melhor posição em que cada jogador pode ser escalado.
 'Best Overall Rating', no Fifa existem várias versões do Overall dos jogadores através de cartas comemorativas. Essa coluna informa o Overall mais alto que aparece dentre as cartas dos jogadores. Cartas são versões comemorativas dos jogadores que são usadas em um dos modos do jogo.
 'Release Clause', valor da clausula de quebra de contrato de cada jogador, é cotada em euros. 
 'DefensiveAwareness'
 
A seguir, todas as colunas representam o nível de habilidade do jogador, que são medidas de 0 a 100 onde 100 representa o máximo de habilidade possível e 0 sem habilidade nenhuma, para fazer a ação determinada pelo nome da coluna. Assim, quanto maior o valor do jogador em 'Crossing', melhor o jogador efetuará cruzamentos no jogo. 

 'Crossing',
 'Finishing',
 'HeadingAccuracy',
 'ShortPassing',
 'Volleys',
 'Dribbling',
 'Curve',
 'FKAccuracy',
 'LongPassing',
 'BallControl',
 'Acceleration',
 'SprintSpeed',
 'Agility',
 'Reactions',
 'Balance',
 'ShotPower',
 'Jumping',
 'Stamina',
 'Strength',
 'LongShots',
 'Aggression',
 'Interceptions',
 'Positioning',
 'Vision',
 'Penalties',
 'Composure',
 'Marking',
 'StandingTackle',
 'SlidingTackle',
 'GKDiving',
 'GKHandling',
 'GKKicking',
 'GKPositioning',
 'GKReflexes',
