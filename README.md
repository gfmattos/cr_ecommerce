# **e-Commerce Recommendation System**

---

## *Contexto*
Durante a pandemia os números de vendas da Razzle Dazzle (e-commerce de variedades) dispararam, bem como o da concorrência. Uma das maneiras de se destacar nesse mercado cada vez mais competitivo é oferecer o produto certo para a pessoa certa.

Então, você foi contratado desenvolver pelo menos um modelo de recomendação, que será disponibilizado no novo site da empresa. Além do modelo, é necessário informar qual o melhor momento para usá-lo, em propagandas, quando o cliente estiver fazendo uma pesquisa ou quando o cliente estiver vendo um produto. É fundamental que isso seja pensado no desenvolvimento do modelo.

## *conteúdo*

*Datasets*

1. DNC_orders_dataset
2. DNC_order_items_dataset
3. DNC_products_dataset
4. DNC_products_dataset

*Lista de Variáveis:*

1. 	DNC_orders_dataset
    * order_id – Id do pedido de compra;
	* customer_id – Id do consumidor que realizou a compra;
	* order_status – Status da compra;
2. DNC_order_items_dataset
    * order_id - Id do pedido de compra;
	* order_item_id – Número de produtos em uma mesma compra;
	* product_id – Id do produto;
	* price - preço;
3. 	DNC_products_dataset
    * product_id – Id do produto;
	* product_category_name – Categoria do produto;
	* product_name_length – Tamanho do nome do produto;
	* product_description_length – comprimento do produto;
	* products_weight_g – peso do produto em g;
	* products_lenght_cm – comprimento do produto em cm;
	* products_height_cm – Altura do produto em cm;
	* product_widht_cm – largura do produto em cm;
4. DNC_order_reviews_dataset
    * order_id – Id do pedido de compra;
    * review_id - Id da nota atribuida pelo cliente
    * review_score - Nota atribuida pelo cliente

## *Fonte*

Toda informação foi fornecida pela equipe da dnc.group, para ver mais a respeito do case acesse a apresentação [`AQUI`](./data/.pdf/[DEX]_DAY_7_Template.pdf)

---

Esta análise foi criada por [Guilherme Mattos](https://www.linkedin.com/in/guilhermefmattos/)

Para acessar a análise e a modelagem, por favor, acesse o arquivo [`ecommerce notebook`](./notebooks/ecommerce.ipynb) dentro da pasta "notebooks".

--- 

## **Tabela de Conteúdos**

- [Conteúdos do Notebook](#Notebook-Contents)
- [Definição do Modelo](#Definição-do-Modelo)
- [Exploração dos Dados](#Exploração-dos-Dados)
- [Estruturação dos Dados](#Estruturação-dos-Dados)
- [Tratamento](#Tratamento)
- [Criação do Modelo](#Criação-do-Modelo)
- [Teste do Modelo](#Teste-do-Modelo)
- [Resultados](#Resultados)
- [Conteúdo Extra](#Conteúdo-Extra)

### **Conteúdos do Notebook**

| Sections |
| ------- |
| [0. Bibliotecas](./notebooks/heart_disease.ipynb/#0.-Bibliotecas) |
| [1. Datasets](./notebooks/heart_disease.ipynb/#1.-Datasets) |
| [2. Análise Exploratória](./notebooks/heart_disease.ipynb/#2.-Análise-Exploratória) |
| [3. Feature Engineering](./notebooks/heart_disease.ipynb/#3.-Feature-Engineering) |
| [4. Modelagem](./notebooks/heart_disease.ipynb/#4.-Modelagem) |
| [5. Resultados](./notebooks/heart_disease.ipynb/#5.-Resultados) |

*EM CONSTRUÇÃO*

### **Definição do Modelo**

Modelo escolhido: Filtro Colaborativo, utilizando uma matriz de relacionamento de produto com cliente que executaram a compra

### **Exploração dos Dados**

Os dados trazem 

### **Estruturação dos Dados**



### **Tratamento**



### **Criação do Modelo**



### **Teste do Modelo**



### **Resultados**



### **Conteúdo Extra**
