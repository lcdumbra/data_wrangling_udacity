# Data Wrangling Udacity
Projeto realizado no curso "Fundamento de Data Science II" da Udacity

Meta:
Fazer wrangling dos dados de tweets de WeRateDoga para que você possa criar análises e visualizações interessantes e confiáveis. Sim, WeRateDogs deu à Udacity acesso exclusivo a seu arquivo de tweets, mas ele contém informações muito básicas. Coleta, avaliação e limpeza adicionais são necessárias para análises e visualizações que mereçam uma reação de "Uau!"

Contexto:
Este arquivo contém dados básicos de tweets para os mais de 5000 de seus tweets, mas não tudo. Uma coluna o arquivo contém com certeza: cada texto de tweet, o que eu usei para extrair classificação, nome e "estágio" do cachorro (ou seja, doggo, floofer, pupper e puppo).

Detalhes do projeto:

Data wrangling, que consiste em:
Coletar dados
Avaliar dados
Limpar dados
Armazenar, analisar e visualizar seus dados wrangled
Elaborar relatórios sobre 1) seus esforços de data wrangling 2) suas análises e visualizações de dados

Coletando dados para esse projeto:

Colete cada um dos três pedaços de dados conforme descritos abaixo em um notebook Jupyter intitulado wrangle_act.ipynb.

O arquivo WeRateDogs. Estou dando este arquivo a você, então o imagine como um arquivo já em mãos. Baixe este arquivo manualmente clicando no link a seguir: twitter_archive_enhanced.csv

As previsões de imagens em tweets, isto é, qual raça de cachorro ou objeto inanimado está presente em cada tweet Este arquivo (image_predictions.tsv) está hospedado nos servidores da Udacity e devem ser baixados programaticamente usando a seguinte URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

A contagem de retweets e favoritos (curtida) de cada tweet, no mínimo, e quaisquer dados adicionais que você achar interessantes. Faça uma consulta na API do Twitter (usando as ID de tweets no arquivo do Twitter de WeRateDogs) para o conjunto de dados completo de cada tweet usando a biblioteca Tweepy do Python e armazene esses dados em um arquivo chamado tweet_json.txt, onde os dados JSON armazenados de cada tweet devem ser escritos em sua própria linha. Então, leia este .txt linha por linha em um dataframe do Pandas com (no mínimo) ID de tweet, contagem de retweets e contagem de favoritos. Obs.: não inclua suas chaves de API do Twitter e tokens de acesso no envio de seu projeto.

Avaliando dados para esse projeto:

Após coletar cada um dos pedaços de dados acima, os avalie visualmente e por meio de programação para problemas de qualidade e arrumação. Detecte e documente ao menos oito (8) problemas de qualidade e dois (2) problemas de arrumação em seu notebook Jupyter. Para atender às especificações, os problemas que satisfazem a motivação do projeto (ver página anterior) devem ser avaliados.

Limpando dados para esse projeto:

Limpe cada um dos problemas que você documentou enquanto avaliava. O resultado deve ser um dataframe master do Pandas (ou dataframes, caso seja apropriado) de alta qualidade e arrumado. De novo, os problemas que satisfazem a motivação do projeto devem ser limpos.

Armazenando, analisando e visualizando dados para este projeto:

Armazene o(s) dataframe(s) limpo(s) em um arquivo CSV, com o principal deles intitulado twitter_archive_master.csv. Se adicionais existirem, os nomeie de forma apropriada. Além disso, você pode armazenar os dados limpos em um banco de dados SQLite (que também deve ser enviado, caso você o faça).

Analise e visualize seus dados wrangled em seu notebook Jupyter. Pelo menos três (3) insights e uma (1) visualização devem ser produzidos.

Fazendo relatórios para este projeto:

Crie um relatório de 300-600 palavras chamado wrangle_report.pdf que descreva brevemente seus esforços de wrangling. Ele deve ser enquadrado como um documento interno.

Crie um relatório escrito de mais de 250 palavras, chamado act_report.pdf, que comunique os insights e exiba a(s) visualização(ões) produzida(s) por seus dados wrangled. Ele deve ser enquadrado como um documento externo.
