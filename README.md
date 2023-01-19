# House Rocket Analytics
![alt text](https://github.com/GuilhermedeAvila/House_Rocket/blob/main/imagens/For_sale.JPG)

Este projeto se trata de uma simulação sobre ciência de dados em uma empresa do ramo imobiliário. Como resultado do projeto, resolvemos alguns problemas de gerenciamentos de informações, e conseguimos aumentar a margem de lucro da empresa em um total de 19.89%.

## 1. Sobre o Projeto
### 1.1 Problema de Negócio
A House Rocket é uma empresa (fictícia) do setor imobiliário, que tem como modelo de negócio a compra e venda de imóveis localizados em King County - USA, sendo o resultado dessa operação o lucro da empresa.

A House Rocket enfrenta alguns problemas, eles tem um grande conjunto de dados mas não conseguiram tirar muitas informações. Abaixo segue uma lista dos principais problemas que eles enfrentam:
- Precisam fazer algumas análises por conta própria.
- Não aproveitam todo o potencial do conjunto de dados, como a descoberta de insights.
- Eles não sabem quais casas devem comprar e vender, e qual o valor.


### 1.2 Data Overview
| Attribute | Description |
| :----- | :----- |
| id | Código de identificação de cada imóvel |
| date | Data de inserção do imóvel na base |
| price | Preço pedido pelo imóvel |
| bedrooms | Número de quartos |
| bathrooms | Número de banheiros |
| sqft_living | Área construída |
| sqft_lot | Área do terreno |
| floors | Número de andares |
| waterfront | Variável binária indicando se o imóvel tem vista para o mar |
| view | Uma escala de 0 a 4 indicando a qualidade da vista do imóvel |
| condition | Uma escala de 0 a 5 indicando as condições do imóvel |
| grade | Uma escala de 1 a 13 indicando a qualidade da construção e padrão arquitetônico |
| sqft_above | Área construída acima do solo |
| sqft_basement | Área construída do porão |
| yr_built | Ano de construção do imóvel |
| yr_renovated | Ano da última reforma |
| zipcode | Código postal do imóvel |
| lat | Latitude |
| long | Longitude |
| sqft_living15 | Área construída dos 15 vizinhos mais próximos |
| sqft_lot15 | Área do terreno dos 15 vizinhos mais próximos |

Dataset from Kaggle
[![kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/harlfoxem/housesalesprediction)

### 1.3 Solução

**1.3.1 Aplicação para analises:** Uma aplicação no StreamlitCloud. Um dashboard interativo, onde se e possível fazer suas próprias análises.

<img src= "imagens/dash_streamlit.jpg"  width="600">
&nbsp;

<img src= "imagens/dash_streamlit2.jpg"  width="600">

&nbsp;

House Rocket APP
[![House Rocket App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://guilhermeavila-houserocket.streamlit.app/)

**1.3.2 Insights:** Os insights gerados pela visualização de dados, estão na imagem abaixo. Ou para uma melhor visualizacao recomendo ver os insights no arquivo do jupyter notebook.

 [House Rocket Jupyter Notebook Codes](https://github.com/GuilhermedeAvila/House_Rocket/blob/main/Insight%20-%20Apartments.ipynb)

![alt text](https://github.com/GuilhermedeAvila/House_Rocket/blob/main/imagens/jupyter_notebook.JPG)


**1.3.3 Compra e vendas de imóveis:** Um relatório com os imóveis a serem comprados, e o valor a serem vendidos. Os imóveis serão selecionados pelas seguintes condições:
- O valor dos pés quadrados do imóvel tem de estar abaixo da mediana, do valor dos pés quadrados da sua região (zipcode).
- Condição dos imóveis tem de estar igual ou acima de 3.

O relatório pode ser acessado aqui: [casas_para_comprar.xlsx](https://github.com/GuilhermedeAvila/House_Rocket/blob/main/casa_para_comprar.xlsx)

**1.4.4. Resultado Financeiro das Recomendações:** O custo de todos os imóveis a serem comprados é de $ 5.163.360.430 (Dólar). Caso as recomendações forem implantadas, o potencial total do lucro obtido com as vendas recomendadas sera de $ 1.026.992.389,60 (Dólar) - 19.89% de lucro. Por se tratar de um valor alto, eu recomendo que se inicie a operação com as casas que tem como nível de condições igual ou maior que 3, com o ano de construção acima de 2000, pois são as casas mais atuais e esteticamente melhores, com um visual atraente, podendo assim realizar um marketing com mais facilidade.


## 2. Tecnologias Utilizadas
- Python 
- VSCode
- Jupyter Notebook
- Streamlit
- Streamlit Cloud

## 3. Arquivos do projeto
 [House Rocket Jupyter Notebook Codes](https://github.com/GuilhermedeAvila/House_Rocket/blob/main/Insight%20-%20Apartments.ipynb)
 

## 4. Próximos passos
- Projetar e executar testes para isolar causas e efeitos
- Recomendar mudanças nas táticas ou gastos para melhorar os resultados
- Identificar grupos e subgrupos de clientes e prospectos

## 5. Agradecimentos
Projeto desenvolvido ao decorrer  do curso *Python: do zero ao Data Scientist* - [Comunidade DS](https://comunidadeds.com/).

Gostaria de agradecer ao professor e cientista de dados [Meigarom Lopes](https://www.linkedin.com/in/meigarom/) pelos ensinamentos!

## 6. Contato
Projeto criado por [Guilherme de Ávila.](https://www.linkedin.com/in/guilherme-de-%C3%A1vila-rodrigues-orlando027/)

[Portfolio de Projetos]()

[![Linked In](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-de-%C3%A1vila-rodrigues-orlando027/)
