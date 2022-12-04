
# Salário Mínimo - Brasil
O objetivo deste projeto é coletar dados das APIs abertas do Banco Central do Brasil, Webscraping no site do Dieese, preparar e analisar os dados usando Python.
<br>
Fonte de dados:
<br>
API Banco Central - [SGS - Sistema Gerenciador de Séries Temporais - Banco Central](https://www3.bcb.gov.br/sgspub/localizarseries/localizarSeries.do?method=prepararTelaLocalizarSeries). 
<br>
WebScraping - [Site do Dieese](https://www.dieese.org.br/analiseicv/tarifasPublicas.html)
<br>
<br>
<b>Modulos utilizados:</b> Numpy, Pandas, Matplotlib, Requests, BeautifulSoup, json.
<br>
<br>
<b>Passo a passo:</b>  
<br>
**API Banco Central**
<br>
<b>Passo 1:</b> Criação de Função para consulta.
<br>
<b>Passo 2:</b> Definição dos códigos BCB que serão consultados e convertidos em DataFrame.
<br>
<br>
**Webscrapping Dieese**
<br>
<b>Passo 1:</b> Extraindo HTML de uma página da web.
<br>
<b>Passo 2:</b> Direcionando elementos de interesse dentro do HTML.
<br>
<b>Passo 3:</b> Armazenar os dados dentro de um DataFrame.
<br>
<b>Passo 4:</b> Ajustes finos de elementos direcionados com Regex (expressões regulares), conversão de string e remoção de elementos html indesejados.
<br>
<b>Passo 5:</b> Analisando os dados e criando visualizações.
<br>
<br>
<b>Jupyter Notebook:</b> [Tarifas Públicas - Dieese](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/Tarifas_Publicas_DIEESE.ipynb)
<br>
<b>Autor:</b> Oscar Monteiro
<br>
<b>LinkedIn:</b> [Oscar Monteiro](https://www.linkedin.com/in/oscarmonteiro98/)

