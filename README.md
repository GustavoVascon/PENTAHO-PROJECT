# PENTAHO-PROJECT

![Penatho](https://user-images.githubusercontent.com/92761995/222937918-cf93b38d-afa2-42ca-8685-b751c4b3cca8.jpg)

## <h3>Do que se trata o projeto?<h3/>

<p>Utilização do Pentaho(transformações, jobs e suas demais ferramentas) para o tratamento de dados(ETL), automação através do arquivo .bat e criação do Data Warehouse.<p/>

## <h3>Motivo de seu Desenvolvimento<h3/>

<p>Foi desenvolvido para que eu compreendesse os processos de ETL através do Pentaho e um melhor entendimento de como construir um Data Warehosue, seus processos
e sua automação.<p/> 

##

<h3>O Projeto<h3/>

<p>Como visto na primeira imagem, o banco de dados base se encontra no SQL Server.
Foi desenvolvido uma conexão do Pentaho com SQL SERVER para a extração(E) de seus dados e alocação para o Stage no PostgreSQL.
<p/>

![sql server - pentaho conexao](https://user-images.githubusercontent.com/92761995/222993294-8f1e3c2d-7b8a-44af-b08d-59574bc93bc0.png)

##
  
<h3>Stage PostgreSQL<h3/>
 
![Captura de tela 2023-03-05 205916](https://user-images.githubusercontent.com/92761995/222993582-49c52df7-38e8-428b-be78-aedf36965615.png)

##
  
<h3>DER Data Warehouse<h3/>

![DATA WAREHOUSE - DIAGRAMA](https://user-images.githubusercontent.com/92761995/222993007-eb79e4f5-1aa7-4c1d-bb8c-e28ed8e21a89.png)

##
  
<h3>Transformação<h3/>

Os processos de transformação foram: 
  
Análise de vendas por Região. <br/>
Análise de vendas por Produto. <br/>
Armazenar o histórico de produtos com a categoria e subcategoria. <br/>
Análise de compra por Cliente. <br/>
Nome completo do cliente (Primeiro Nome + Último Nome) <br/>
Análise ao longo do Tempo. <br/>
Dia, semana, mês, trimestre, semestre, ano... <br/>

<h3>Dimensão Cliente<h3/>

![Captura de tela 2023-03-05 211334](https://user-images.githubusercontent.com/92761995/222996612-a6abaab0-5d3a-4c11-98d4-2820876a22ce.png)

<h3>Dimensão Produto<h3/>

![Captura de tela 2023-03-05 211300](https://user-images.githubusercontent.com/92761995/222996639-b3231f4a-5980-4b77-8a3b-35eda9f67ba5.png)

<h3>Dimensão Tempo<h3/>

![Captura de tela 2023-03-05 211418](https://user-images.githubusercontent.com/92761995/222997812-5b864d21-211c-4b87-be3f-0345557ec34f.png)
  
##  

<h3>Fato<h3/>

![Captura de tela 2023-03-05 211440](https://user-images.githubusercontent.com/92761995/222997841-d1cded3a-f686-4657-9177-1182f9fcac0f.png)

##  

<h3>Data Warehouse PostgreSQL<h3/>

![Captura de tela 2023-03-05 221233](https://user-images.githubusercontent.com/92761995/222998171-863d89d7-e494-4035-8b9e-644edcb61a0d.png)


