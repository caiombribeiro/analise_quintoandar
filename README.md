<h1 align="center"> Analise e predição de dados no mercado imobiliário de São Paulo/SP</h1> 

<p>O intuito desse projeto é a criação de uma analise preditiva para encontrar o valor de um imóvel com base em variáveis e um database focado na empresa Quinto Andar e Rede Social de Cidades.</p>

<h2>Etapas do projeto</h2>

<h3>0. Motivação</h3>

<p>Supondo que há o desejo de compra ou aquisição de um imóvel na cidade de São Paulo. Para isso, é preciso encontrar um modelo para que seja possivel, por meio de variáveis bem delimitadas, encontrar o valor de acordo com variáveis diversas desde caracteristicas do imóvel até o IDH da região.</p>

<h3>1. Coleta de Dados</h3>

<p> Para fazer a devida coleta, foram utilizados os pacotes e bibliotecas descritas abaixo. Foi utilizado como dataset o Kaggle Sao Paulo housinf prices (https://www.kaggle.com/datasets/renatosn/sao-paulo-housing-prices) e o site Agente Imovel (https://www.agenteimovel.com.br/mercado-imobiliario/a-venda/sp/sao-paulo/) para encontrar os valores do m² de cada bairro. Também foi utilizado o site do Wikipedia para delimitar os bairros do Dataset Kaggle, para existir apenas bairros da cidade de São Paulo no dataframe.</p>

<h3>2. Preparação dos Dados</h3>

<p> Aqui temos 2 etapas: o processamento da geolocalização com base nos endereços dos imóveis e a unificação de todos os dados da fase de coleta para um dataframe Pandas. Com a geolocalização, é possivel definir os imóveis dentro da região da cidade de São Paulo para posteriormente criar um mapa regional. Na questão do dataframe, foi adicionado um arquivo XLSX coletado pelo site Rede Social de Cidades, trazendo mais variáveis para a etapa de modelagem.</p>

<h3>3. Modelagem de Dados</h3>

<p>Com os dados processados, foi possivel usar a modelagem de dados devida. Os dados foram padronizados para melhor acuidade do modelo, tanto as variáveis numéricas quanto categóricas. Foi feito o treino e teste, assim como utilizado para definição do modelo a regressão linear. O indice do RMSE encontrado foi de 21,36%, um valor aceitável considerando a quantidade limitada de variáveis definidas.</p>

<h3>4. Visualização</h3>

<p>Aqui foi gerado 2 gráficos. O primeiro gráfico de localização dos imóveis em cada bairro de SP, considerando a diferenças de tipos. O segundo é a comparação entre o modelo apresentado e os valores testes, demonstrando a acuidade do modelo. </p>

<h3>5. Resultado</h3>

<p>O efeito foi testado com um conjunto de dados de um imóvel desejado, considerando todas as condições. Foi entregue um resultado que possui uma grande chance de assertividade (79%).</p>

<h2>Tecnologia, Pacotes e Bibliotecas</h2>

<li>Python</li>
<li>Jupyter Notebook</li>
<li>Pacotes e Bibliotecas</li>
<ul>Requests</ul>
<ul>BeautifulSoup</ul>
<ul>Pandas</ul>
<ul>Seaborn</ul>
<ul>Numpy</ul>
<ul>Geopandas</ul>
<ul>Geopy e Nominatim</ul>
<ul>Matplotlib</ul>
<ul>Scikit-learn</ul>

<h2>Contato</h2>
<p>Caio Marques - <a href="https://www.linkedin.com/in/caiombr/">LinkedIn</a></p>

