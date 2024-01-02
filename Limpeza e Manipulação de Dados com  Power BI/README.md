# **Sobre o projeto**

Esse foi um projeto muito importante, pois adquiri conhecimentos fundamentais. O projeto foi desenvolvido juntamente com o curso que conclui. Ele foi baseado em análise de dados gerais, como limpeza, manipulação e processamento de dados, e não em típicas atividades de projetos de BI (Business Intelligence).

### **Desenvolvimento do Projeto**

O relatório era composto por: 

> **Valores Null**: ausência de dados.

Para sanar o problema, retiramos a **média,** que seria a soma dividida pela quantidade de elementos.

O **desvio padrão** é a raiz quadrada da variância, medindo a dispersão, então, se um desvio padrão for maior, indica maior variabilidade dos valores, enquanto um desvio padrão menor sugere que os valores estão mais próximos da média.

Para a **mediana**, ordenamos os dados de forma crescente, somamos os valores do meio e dividimos por 2 se forem pares, se é ímpar, a mediana será representada por esse valor. 

**Valores Null:** foram substituídos pela mediana que são os valores mais próximos da média. 

> **Valores Duplicados**

Realizamos a contagem de ID's, pois, nessa base de dados, o ID deve ser algo único, como se fossem dados de RG ou CPF, por exemplo, sendo assim foi determinado que o ID seria um por pessoa. 

Ao realizarmos a contagem e a contagem distinta, foi identificado uma diferença entre os números, sendo assim, decidi realizar a retirada desses valores duplicados, pois, não teria impacto nas análises. 

> **Detecção e tratamento de outliers**

Realizei o tratamento de outliers, que basicamente é tratar os valores extremos que podem afetar as nossas análises. E o dado extremo identificado foi a altura, substituída pela mediana. 
Então, criei novas medidas para identificar os quartis para que eu pudesse entender a dispersão dos dados e identificar a presença de valores extremos. 
As informações que estão acima da linha azul (limite superior) são os outliers. 

**Q2** - Mediana

**IQR** - Intervalo interquartis, que seria a distância entre o Q3 e Q1. 
