📊 Projeto Final - Segmentação de Clientes com K-Means

Este é o projeto final do Módulo 33 - Modelos Avançados, com o objetivo de aplicar os conceitos de clustering para segmentar clientes de um shopping com base em dados demográficos e comportamentais, utilizando o algoritmo K-Means.

📅 Objetivo

Aplicar técnicas de:

Exploração e tratamento de dados

Transformação de variáveis

Padronização

Implementação e avaliação do algoritmo K-Means

📈 Dataset

O dataset utilizado contém informações de 200 clientes, com os seguintes atributos:

CustomerID: Identificador único do cliente

Gender: Gênero

Age: Idade

Annual Income (k$): Renda anual em milhões de dólares

Spending Score (1-100): Score de gastos com base no comportamento do cliente

📝 Etapas do Projeto

1. Análise e Limpeza dos Dados

Verificação de valores nulos

Análise univariada (histogramas e distribuições)

Análise bivariada para identificar relações entre variáveis

2. Tratamento da Variável Categórica

A variável Gender foi convertida usando One-Hot Encoding

Criada a variável Genero_Male, onde 1 representa masculino e 0 feminino

A coluna original foi removida após a conversão

3. Visualização

Uso do pairplot para explorar relações entre variáveis numéricas

4. Padronização dos Dados

Foi utilizada a padronização via StandardScaler para normalizar as variáveis

5. Aplicação do Algoritmo K-Means

KMeans aplicado com k=5

Atribuição de labels aos clientes conforme seus clusters

Visualização por matriz de dispersão

6. Visualização da Matriz de Dispersão e Interpretação dos Clusters

Com base na matriz de dispersão, o valor de k = 5 mostrou-se adequado, resultando nos seguintes perfis:

Cluster 0: Renda alta, idade baixa, score alto

Cluster 1: Renda média/alta, idade dispersa, score baixo

Cluster 2: Renda média, idade média, score médio

Cluster 3: Renda baixa, idade baixa, score alto

Cluster 4: Renda média, idade alta, score médio

🔍 Os clusters indicam 5 perfis distintos de clientes. Observa-se que clientes mais jovens tendem a apresentar scores de gasto mais altos, mesmo com renda mais baixa. Isso sugere que as vendas do shopping estão concentradas no público jovem.

💡 Sugestões por Perfil de Cliente

🎯 Jovens

Ações com influenciadores digitais

Eventos e promoções voltadas ao público jovem

👥 Clientes mais velhos com renda alta 

Programas de fidelidade

Melhoria da experiência de compra

🛍️ Perfil médio (cluster 2)

Ofertas sazonais

Brindes e sorteios para estimular o consumo


📅 Conclusão
A aplicação do K-Means permitiu segmentar eficientemente os clientes, revelando perfis distintos e oportunidades claras de ações direcionadas.

🎓 Projeto desenvolvido para consolidação dos conhecimentos em modelagem avançada.
