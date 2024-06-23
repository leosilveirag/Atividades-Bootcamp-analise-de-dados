<h1 align= "center"> PROJETO Final + Atividade ETL </h1>

## PROJETO FINAL
Projeto FInal de conclusão do bootcamp da SoulCode de análise de dados onde em grupo deveríamos realizar a escolha de um conjunto de dados com a temática da saúde. Inicialmente escolhemos uma base de dados do Kaggle sobre a saúde do sono e o estilo de vida. Para esse trabalho criamos um storytelling que estavamos prestando uma consultoria para uma clínica do sono e através de dados disponibilizados da clínica de seus pacientes colhidos através de entrevistas queriam que verificassemos como estaria a o sono e o estilo de vida dos pacientes e que no final poderiamos propor insights para a empresa.

Iniciamos o trabalho armazenando esses dados na Google Cloud e na Big Query. Após isso carregamos no Jupyter Notebook utilizando a ferramenta Google Colab. Para o projeto usamos o Python como linguagem de programação para realizar as tarefas e a biblioteca Pandas para podemos alterar colunas, traduzir dados, excluir colunas, ver se existem valores nulos, alterar alguns tipos de dados, verificamos se existiam colunas duplicadas e por fim verificar com o pacote pandera a integridade dos dados se estava tudo correto. 

Depois disso, carreguei e salvei os dados novamente no google Cloud e na Big Query para armazenamento e depois para carregar em um dashboard. Através do Matplotlib conseguimos exibir gráficos e assim visualizar algumas questões previamente no próprio Colab como a dispersão da Qualidade do Sono vs. Nível de Estresse e verificar o  Nível de Atividade Física por Categoria de IMC.

Após isso, extraimos os dados já modificados e organizados da BigQuery e carregamos eles usando o PowerBi para montar um Dashboard com gráficos interativos mostrando análises interessantes sobre o estilo de son oe de vida das pessoas entrevistadas. 

## Conclusões através da visualização do Dashboard

Realizamos dois dashboards, o primeiro se referenciava a qualidade do sono e a duração do sono. Primeiro mostramos que temos 374 pacientes onde a idade média é de 42 anos e em um primeiro gráfico  analisamos a média qualidade de sono por gênero e as mulheres tem uma média de qualidade de sono melhor que a dos homens. No segundo gráfico fizemos a média de duraçÃo do sono por ocupação dos entrevistados e os que tem menos duração seriam vendedor, cientista e representante de vendas e com os melhores indíces de duração do sono seriamcontador, advogado e engenheiro. Em seguida analisamos a média duração de sono por qualidade do sono e quem tem mais qualidade do sono tem uma maior duração do mesmo. E por último, analisamos a média da qualidade do sono por nível de estresse e concluímos que quanto maior o estresse menor a qualidade de sono. 
No segundo dashborad, abordamos questões mais ligadas a saúde e sono e conseguimos verificar que existe um queda na qualidade do sono para pessoas obesas. No próxim slide percebemos que quem mantém atividade física por mais tempo tem mais qualidade de sono. Realizamos um gráfico por gênero e disturbio do sono que verifiamos que as mulheres sofrem mais com apinéia do sono e insônia do que os homens e que bastante homens não informaram sobre sua condição do sono. Depois realizamos nível médio de estresse por distúrbio e vimos que quanto maior o estresse mais frequente são os distúrbios do sono. 

Neste projeto participei ativamente de todas as etapas do projeto tanto ajudando técnicamente como ajudando a fazer a gestão do projeto, participando ativamente de todas as etapas, pois optamos com ogrupo resolver juntos todas as etapas para todos participarem e darem opinião sobre cada etapa e asssim ajudando no aprendizado que foi passado do bootcamp. 

<h2 align= "center"> Atividade ETL </h2>

Atividade proposta em aula do bootcamp da SoulCode de análise de dados onde em grupo deveríamos realizar o processo de ETL (Extract, Transform e Load) de um conjunto de dados públicos de uma empresa qualquer, neste caso especificamente era com o objetivo de avaliar as informações coletadas dos clientes e suas compras para poder analisar medidas de marketing futuramente. Após a realização da ETL se fosse possível, gerar alguns gráficos para analisar dados que pudessemos considerar importante. 

Antes de iniciar a ETL, armazenamos o conjunto de dados em formato CSV dentro do serviço de nuvem google cloud storage e habilitamos o acesso para todos os integrantes do grupo caso fosse necessário alguém ter o acesso dos dados. Após isso, usamos o Google Colab para fazer todo o processo utilizando a linguagem Python. Trouxemos os dados da Storage para o colab e para realizar o processo de ETL, utilizamos a biblioteca pandas do python. Nesse processo tivemos a extração e carregamento dos dados no colab, alteramos as colunas, traduzimos células e colunas, verificamos se existiam valores nulos, alteramos alguns tipos de dados como de float para int, verificamos colunas duplciadas, alteramos o tipo de data, verificamos se tinha consistências e utilizamos por fim, o pacote pandera para verificar a integridade do nosso processo de ETL. 

Depois disso, carreguei o conjunto de dados tratados primeiramente no google drive para poder salvar como segurança e em definitivo carregamos no google storage para armazenamento. 
Através do Matplotlib conseguimos exibir gráficos e assim visualizar algumas questões como a média de compras por categoria de produto através de um gráfico de barras, o total de compras de vinhos por Estado Civil também por um gráfico de barras e a quantidade de cliente nos anos 2012, 2013, 2014 através de um gráfico de pizza. 

Nesta atividade realizada, participei ativamente principalmente do processo de ETL do começo ao fim, realizando junto aos meus colegas de curso a atividade de maneira muito compromissada e satisfatória. 


