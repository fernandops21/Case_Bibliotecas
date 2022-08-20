# Case_Bibliotecas
Resolução Case utilizando bibliotecas: numpy, pandas, matplotlib, seaborn  
  
  
Na era digital em que se vive atualmente, principalmente durante e pós a Pandemia, a utilização da internet na coleta de dados, troca de comunicações e criação de novas operações dentro da nuvem (online). Com esse advento da necessidade de internet no nosso dia a dia, diversas novas empresas veem surgindo ao longo do mundo, oferecendo novos pacotes mais baratos e mais acessíveis a toda população.  Neste contexto, você utilizando o dataset Internet Prices around 200+ countries in 2022, onde consta o levantamento de dados acerca dos planos de internet e população de mais de 200 países. Seu objetivo é ler e entender os 3 datasets apresentados, que se completam em dados e informações. Ao final desse entendimento, responder as 10 perguntas abaixo:  
  
1 - Quantas empresas foram consultadas?  
2 - Calcule a Variação percentual entre o preço médio da internet entre o início 2020 e 2021, usando como base o preço de 2021.   
3 - Calcule o preço médio geral da internet dos países que sejam da SOUTH AMERICA.   
4 - Dos países que foram avaliados, qual os 5 países que tem a maior taxa de usabilidade de internet em relação a população?   
5 - Faça um gráfico que mostre o número de países que apresentem uma taxa de usabilidade maior que 75% agrupados por Continente?   
6 - Calcule a amplitude de preço entre os planos de internet.  
7 - Usando somente o seabron e matplotlib, construa um gráfico que mostre o valor médio, máximo e mínimo dos maiores preços para cada região.   
8 - Supondo que a gente more no Reino Unido (United Kingdom), usando a velocidade média e o preço médio, quantos Dolares eu pagaria se utiliza-se uma hora de internet?  
9 - Utilizando os mesmos parâmetros da etapa anterior, supondo que você seja um dono de uma empresa que precisa instalar a internet no prédio e precisa fazer um orçamento. A empresa responsável disse que se você contratar um pacote até 50000Gb por dia é 300 Dolares, até 65000 é 350 Dolares e acima disso é 450 Dolares. Supondo que você tenha 300 funcionários, trabalhando 8 horas no dia, qual plano seria ideal para você?  
10 - Somente com uma visualização gráfica, comparando o preço médio em 2020 e 2021, com uma linha de tendência (Gráfico identidade x = y), conclusa se o preço médio da internet ficou mais barato ou caro de 2020 para 2021.   
  
Instruções primordiais: Alguns dados estão ausentes nos 3 datasets, mas representam pouco perto da análise total. Portanto, utilize os 3 datasets fornecidos (df1,df2,df3).  
  
df1 - Descritivo das colunas do dataset:   
country_code - Country code   
country_name - Country Name   
country_continental - Continental region   
num_internet_plans - Num. of internet Plans   
avg_price - Average price of 1GB (USD)   
min_price - Cheapest 1GB for 30 days (USD)   
max_price - Most expensive 1GB (USD)   
avg_price_start_2021 - Average price of 1GB (USD at the start of 2021)   
avg_price_start_2020 - Average price of 1GB (USD – at start of 2020)   
  
df2 - Descritivo das colunas do dataset:    
country_name - Country Name   
avg_speed - Avg speed in (Mbit/s) by Ookla   
  
df3 - Descritivo das colunas do dataset:    
country_name - Country Name   
country_subregion - Country subregion   
country_region - Continental region   
internet_users - Num. of people who uses internet Plans   
population - population of country  
