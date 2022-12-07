
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
<b>Jupyter Notebook:</b> [Salário Mínimo - Brasil](https://github.com/MonteiroOscar98/Salario-Minimo-Brasil/blob/main/Salario_Minimo_Brasil.ipynb)
<br>
<b>Autor:</b> Oscar Monteiro
<br>
<b>LinkedIn:</b> [Oscar Monteiro](https://www.linkedin.com/in/oscarmonteiro98/)
<br>
<br>
Resultados:
<br>
<br>
![1](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/1.png)
<br>
<br>
![2](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/2.png)
<br>
<br>
![3](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/3.png)
<br>
<br>
![4](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/4.png)
<br>
<br>
![5](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/5.png)
<br>
<br>
![6](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/6.png)
<br>
<br>
![7](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/7.png)
<br>
<br>
![8](https://github.com/MonteiroOscar98/Tarifas-Publicas-SP-Dieese/blob/main/README_files/8.png)
