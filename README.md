# Manipulando dados com Pandas, Polars e PySpark

Escrito por Rafael Ribeiro de Lima. Linkedin: https://www.linkedin.com/in/rafarlima/

<img src=./images/databanner.png>

A Manipulação, preparação e organização de dados é essencial para aumentar a qualidade dos dados e informações. Todo esse trabalho é para possibilitar que você e sua empresa sejam capazes de usar e confiar com eficácia nos dados disponíveis.
Para que isso seja possível é necessário conhecimento em alguma biblioteca/linguagem de manipulação. Em python as mais utilizadas são a Pandas, Polars e PySpark. 

#### Pandas

O Pandas é uma poderosa biblioteca de código aberto para manipulação e análise de dados em Python. Ela oferece estruturas de dados flexíveis e eficientes, como o DataFrame, que permite armazenar e manipular conjuntos de dados de forma tabular. O Pandas simplifica tarefas comuns, como limpeza de dados, agregação, filtragem e visualização, facilitando a exploração e análise de dados. Além disso, integra-se bem com outras bibliotecas populares, como NumPy e Matplotlib, tornando-a uma ferramenta essencial para cientistas de dados, analistas e desenvolvedores que lidam com dados em Python.

#### Polars

O Polars é uma biblioteca de processamento de dados rápida e eficiente, projetada para lidar com grandes conjuntos de dados em Python e Rust. Ele oferece uma estrutura de dados principal chamada DataFrame, que compartilha semelhanças com o DataFrame do Pandas, mas com um foco especial em desempenho. O Polars é otimizado para operações de dados em paralelo e utiliza tecnologias como Arrow para acelerar a transferência de dados entre diferentes sistemas. Com funções convenientes para manipulação de dados, consultas e agregações, o Polars é uma escolha valiosa para aplicações que demandam processamento rápido e eficiente de grandes volumes de dados.

#### PySpark

O Spark foi projetado para ser altamente escalável, sendo capaz de processar grandes volumes de dados distribuídos entre muitos computadores. Ele fornece APIs em várias liguagens de programação. A manipulação de dataframes utilizando a API da linguagem Python é feita com a biblioteca PySpark. O PySpark é ideal para tarefas de análise de dados, como machine learning, procesamento de texto, análise de dados em tempo real e muito mais. O PySpark oferece muitas vantagens para empresas que precisam lidar com grandes volumes de dados, como redução de custos, escalabilidade, flixibilidade e eficiência.

O Objetivo desse hands-on é fazer uma breve introdução dessas três bibliotecas e passar os principais comandos de cada uma. Para executar é necessário ter o python e o Jupyter Notebook instalados.

O Notebook com o código foi disponibilizado no meu github e pode ser acessado <a href='https://github.com/rafaelrlima/pandas_polars_pyspark/blob/main/Pandas%20vs%20Polar%20vs%20PySpark.ipynb'>clicando aqui</a>.

## Instalação / Configuração

Antes de tudo é necessário instalar e configurar as bibliotecas. No prompt de comando digite os comando abaixo. Caso deseje instalar diretamente do jupyter notebook é só incluir o ponto de exclamação na frete do comando pip e executar a célular. 

Ex: !pip install pandas

#### Instalando a biblioteca Pandas

pip install pandas

#### Instalando a biblioteca Polars

pip install polars

#### Instalando o Spark

pip install pyspark

pip install findspark

#### Configurando o Spark

Após instalar o PySpark usando pip é necessário configurar, você deve executar o findspark da seguinte maneira em um Jupyter Notebook ou em seu código Python:

 import findspark

 findspark.init()
