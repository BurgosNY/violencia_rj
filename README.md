# Investigando dados de violência no RJ

Enquanto São Paulo e outros estados dificultam o acesso aos dados de ocorrências policiais, o Rio de Janeiro [liberou para consulta pública](http://www1.folha.uol.com.br/cotidiano/2016/02/1742551-negros-e-pardos-sao-77-dos-mortos-pela-policia-do-rio-em-2015.shtml) as suas informações pra quem quiser investigar por conta própria no site do [Instituto de Segurança Pública](http://www.isp.rj.gov.br/). O governo prefere usar o [Tableau](www.tableau.com), que é uma ferramenta interessante para visualizar dados, mas se você quiser manipular as tabelas ou usar outras formas de visualização, é preciso baixar o programa e converter tudo para .csv. Se você não quer se dar ao trabalho, basta baixar os arquivos de 2015 que eu extraí aqui. São cerca de 5.000 registros de homicídio, quase 10% do total nacional.

## 1. Limpando o csv

Para ficar mais fácil manipular em diferentes programas (como usando o Pandas, do Python), eu tirei os acentos, colunas repetidas e mudei o nome para ficar mais fácil acessar os dados.

## 2. Usando o iPython Notebook

Eu comecei a criar algumas funções para investigar os dados em um [notebook](http://ipython.org/notebook.html). Certamente meu código não é bonito e elegante, mas resolve o que a gente precisa. Vou adicionar informações provavlemente na quinta-feira. Sugestões de dados, coloquem nos comentários.
