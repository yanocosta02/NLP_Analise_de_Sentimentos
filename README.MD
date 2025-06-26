# Análise de Sentimentos e Categorização de Textos com Machine Learning

## Introdução

Este projeto foi desenvolvido como trabalho final da disciplina de **Aprendizado de Máquina** na Universidade Federal do Paraná (UFPR). O objetivo é criar uma aplicação de **Machine Learning (ML)** e **Processamento de Linguagem Natural (NLP)** para realizar **análise de sentimentos** e **categorização de textos**.

### Sobre o Dataset

Utilizamos o **Drug Reviews Dataset**, que contém avaliações de medicamentos feitas por pacientes. As principais colunas incluem:

- **`drugName`**: Nome do medicamento.
- **`condition`**: Condição médica tratada.
- **`review`**: Texto da avaliação do paciente.
- **`rating`**: Classificação de satisfação (1 a 10 estrelas).
- **`usefulCount`**: Contagem de úteis atribuída à avaliação.

Os dados estão divididos em dois arquivos:

- `drugsComTrain_raw.tsv` (treinamento, 75%).
- `drugsComTest_raw.tsv` (teste, 25%).

## Objetivos do Projeto

1. **Análise de Sentimentos**:
   - Classificar as avaliações em **positivas**, **neutras** ou **negativas** com base na coluna `rating`.
2. **Categorização de Textos**:
   - Identificar a condição médica (`condition`) associada a cada avaliação, utilizando o texto da coluna `review`.

## Etapas do Desenvolvimento

### 1. Exploração de Dados (EDA)

- Análise de distribuições e frequências das variáveis (ex.: `rating`, `usefulCount`).
- Descoberta de relações entre variáveis.
- Identificação de outliers e padrões nos dados.

### 2. Pré-Processamento de Dados

- Limpeza e normalização textual (remoção de HTML, stopwords, tokenização).
- Conversão de texto em representações numéricas utilizando **TF-IDF**.

### 3. Construção e Avaliação de Modelos

- Algoritmos utilizados:
  - **Naive Bayes**
  - **Logistic Regression**
  - **Support Vector Machines (SVM)**
  - **Random Forest**
- Métricas de desempenho:
  - Acurácia
  - Matriz de confusão
  - Relatório de classificação (precision, recall, F1-score)

### 4. Visualização e Interpretação de Resultados

- Visualizações gráficas para distribuições e resultados dos modelos.
- Análise dos erros de classificação.

## Tecnologias Utilizadas

- Linguagem: **Python**
- Bibliotecas principais:
  - `pandas`, `numpy` para manipulação de dados.
  - `nltk`, `scikit-learn` para NLP e ML.
  - `matplotlib`, `seaborn` para visualizações.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/yanocosta02/NLP_Analise_de_Sentimentos.git
   ```
2. Abra o notebook no Google Colab ou Jupyter Notebook e execute as células sequencialmente.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Autor

🎓 **Autores:** Vincent Tomio e Yan Oliveira da Costa

📫 Entre em contato: [yanocosta02@gmail.com](mailto:yanocosta02@gmail.com)

---

Qualquer dúvida ou sugestão, entre em contato!
