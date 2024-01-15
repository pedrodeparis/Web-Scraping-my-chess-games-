

Youtube video about the project: https://www.youtube.com/watch?v=EP1w-1g1v7E 


Power BI Dashboard: 

![Texto alternativo](https://i.imgur.com/hymwYMm.gif)

Descrição do projeto abaixo
-------------------





Projeto de Análise de Dados utilizando API do chess.com, biblioteca request, json, pandas, numpy.

Esse foi sem dúvida um dos projetos mais difíceis que fiz, mas foi muito satisfatório. 

Cada vez buscando me aproximar mais do o real e me afastar dos projetos de base de dados prontas, limpas e bonitas, fiz um projeto único, buscando resolver algumas questões que eu mesmo tinha.

Com isso, aqui, vocês vão encontrar um projeto que inclui absolutamente todas etapas de uma análise de dados. 

Para contextualizá-los acerca do projeto, eu sempre amei jogar xadrez, e sou extremamente competitivo e isso me leva a querer sempre melhorar. Com isso, descobri recentemente que o site que eu jogo (chess.com) tem sua própria API, que nos permite extrair alguns dados do site. 

Com isso, comecei utilizando algumas de suas guidelines e obtive, no retorno, outro grande desafio. Os dados estavam dentro de um URL, formato JSON, com algumas keys bagunçadas. 

Meu desafio começou que alguns dos dados que juguei relevante estavam dentro de uma só key, enquanto outros tinham suas próprias. 

Depois de muito quebrar a cabeça, consegui tratar os dados de 700 partidas jogadas no mês de novembro (sim, joguei muito, mas jogo a modalidade blitz e bullet, que correspondem a 180 segundos e 60 segundos, respectivamente). 

Com isso, criei um loop que buscava todas as informações dentro do URL. Com isso, fui ajeitando, criando novas colunas, tratando os dados e deixando-os prontos para análise.

Aqui enfrentei novos desafios, como, por exemplo, agrupar as aberturas, tendo em vista que todas possuem diversas varíaveis. Por exemplo, a Siciliana, dentro dela, tem Variante Dragão/Dragão Acelerado, Variante Najdorf, Variante Fechada e Variante Clássica. Agrupei para que fosse somente Siciliana, para melhor entender se ela me favorece ou não.

Posteriormente, com algumas bibliotecas de visualizações, pude chegar à algumas conclusões, identificar certos padrões e repensar no meu repertório de aberturas. 

Vocês encontram todo código aqui. 


