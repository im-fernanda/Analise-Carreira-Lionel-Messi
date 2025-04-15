<h1 align="center" style="font-weight: bold;"> Análise da Carreira de Lionel Messi </h1>

Este repositório apresenta um projeto prático de análise de dados, desenvolvido com foco em aplicar técnicas essenciais de Data Science utilizando Python e suas principais bibliotecas. A estrutura da base de dados permite uma análise abrangente do desempenho de Messi ao longo dos anos, destacando suas conquistas e estatísticas em diferentes competições até o ano de 2023. 

## 🚀 Sobre o Projeto

Neste projeto, trabalhei com um conjunto de dados relacionados à avaliação de uma unidade curricular de ciência de dados. A análise teve como foco avaliar estatisticamente e preditivamente os dados com diferentes etapas: desde análise exploratória e limpeza até clusterização e predição, com o objetivo de extrair padrões e avaliar a qualidade das informações contidas no conjunto de dados.

O dataset original foi retirada do [GitHub](https://github.com/azminewasi/Lionel-Messi-Club-Goals/blob/main/data.csv) e adaptada para a atividade pelo docente Antonino Feitosa.

## 🧪 Executar com Binder
Você pode testar este notebook de forma interativa com o [Binder](https://mybinder.org/v2/gh/im-fernanda/messi-career-analysis/main?urlpath=%2Fdoc%2Ftree%2FProjeto.ipynb).

## 🛠️ Tecnologias Utilizadas
- **Linguagem**: Python 3
- **Ambiente**: JupyterLab

**Bibliotecas principais**:
- pandas, numpy: manipulação e análise de dados
- matplotlib, seaborn: visualização de dados
- scikit-learn: modelagem estatística e machine learning


## 🔍 Etapas do Projeto
### 1. Análise Exploratória de Dados (EDA)
- Classificação das variáveis (quantitativas e qualitativas)
- Estatísticas descritivas (média, mediana, moda, desvio padrão, etc.)
- Verificação de normalidade com histogramas, gráficos Q-Q, densidade
- Identificação de valores ausentes

### 2. Limpeza e Tratamento de Dados
- Preenchimento de dados ausentes com modelos de machine learning (kNN, regressão)
- Justificativa da escolha de algoritmos
- Validação dos modelos com holdout e cross-validation
- Detecção de outliers com Isolation Forest

### 3. Agrupamento e Redução de Dimensionalidade
- Estudo de correlação entre variáveis
- Aplicação de k-means (com validação pelo método do cotovelo)
- Redução de dimensionalidade com PCA
- Visualização dos clusters em 2D

### 4. Modelagem Preditiva
- Definição de variável alvo
- Treinamento de modelos estatísticos e de ML para regressão ou classificação
- Ajuste de hiperparâmetros
- Seleção de variáveis mais relevantes (técnicas de filtro e wrapper)
- Avaliação com matriz de confusão ou gráfico de dispersão



