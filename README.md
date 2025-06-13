# 🧠 Notebooks de Processamento de Linguagem Natural (PLN)

Este repositório reúne os notebooks que desenvolvi durante as aulas e projetos de PLN na FATEC Mauá. A proposta é registrar minha evolução nos estudos — desde os primeiros passos até técnicas mais avançadas de análise de texto usando Python.

---

## 📚 Conteúdo dos Notebooks

### `pln_aula02_Python_e_Bibliotecas`
- **Objetivo:** Introdução ao Python e às bibliotecas mais comuns em PLN.
- **Técnicas/Bibliotecas:** Manipulação de strings, uso básico de `nltk`, `spacy`, `re`.
- **Notas:** Serve como base para os próximos notebooks.

### `pln_aula03_Processamento_de_Texto`
- **Objetivo:** Realizar o pré-processamento de textos.
- **Técnicas:** Tokenização, remoção de stopwords, stemming, lematização.
- **Notas:** Etapa essencial antes de aplicar modelos ou análises mais profundas.

### `pln_aula04_Extracao_de_Características`
- **Objetivo:** Converter texto em vetores numéricos.
- **Técnicas:** Bag of Words, TF-IDF, `CountVectorizer`, `TfidfVectorizer`.
- **Notas:** Fundamental para aplicar machine learning com texto.

### `pln_aula05_Analise_Sintatica`
- **Objetivo:** Analisar a estrutura gramatical das frases.
- **Técnicas:** POS Tagging, análise de dependência, árvores sintáticas com `spacy`.
- **Notas:** Ajuda a entender a função de cada palavra em uma frase.

### `pln_aula06_Interpretacao_Semantica_Gramaticas`
- **Objetivo:** Trabalhar com significado das frases e gramáticas formais.
- **Técnicas:** Gramáticas com `nltk`, análise semântica, árvores sintáticas manuais.
- **Notas:** Introduz conceitos de linguística computacional.

### `pln_aula07_Descoberta_Conhecimentos_Textos`
- **Objetivo:** Extrair padrões e informações úteis de textos.
- **Técnicas:** Named Entity Recognition (NER), coocorrência, nuvem de palavras.
- **Notas:** Muito usado em análises exploratórias.

### `pln_aula10_Analise_Sentimentos`
- **Objetivo:** Identificar sentimentos em textos.
- **Técnicas:** Classificação de polaridade, léxicos de sentimentos, visualizações.
- **Notas:** Aplicações diretas em redes sociais, reviews etc.

### `pln_aula11_Machine_learning`
- **Objetivo:** Usar modelos de machine learning com dados textuais.
- **Técnicas:** Classificação, validação cruzada, métricas de desempenho.
- **Notas:** Começo da integração entre PLN e aprendizado de máquina.

### `pln_aula12_13_Redes_Neurais`
- **Objetivo:** Aplicar redes neurais em PLN.
- **Técnicas:** Word embeddings, redes neurais simples com `Keras` e `TensorFlow`.
- **Notas:** Introdução ao uso de deep learning com linguagem natural.

---

## 📂 Projetos

### `pln_projeto01_Corpus`
- **Objetivo:** Construir e explorar um corpus textual.
- **Técnicas:** Coleta, limpeza e análise exploratória.
- **Notas:** Base para projetos aplicados com dados reais.

### `pln_projeto02_Analise_Estatistica`
- **Objetivo:** Aplicar estatísticas básicas em textos.
- **Técnicas:** Frequência de palavras, medidas de tendência central e dispersão.
- **Notas:** Combina conceitos de estatística com linguagem natural.

### `pln_projeto03_Analise_Relevancia`
- **Objetivo:** Avaliar a relevância de termos em documentos.
- **Técnicas:** TF-IDF, visualização de palavras-chave.
- **Notas:** Complementa os estudos de vetorização com foco prático.

---

## ✅ Requisitos
- Python 3.x  
- Bibliotecas utilizadas:
  - `nltk`
  - `spacy`
  - `scikit-learn`
  - `matplotlib`
  - `wordcloud`
  - `pandas`

---

## ⚙️ Observações
- A sequência dos notebooks segue uma lógica de aprendizado progressivo.
- Recomendo o uso no **Jupyter Notebook** ou **Google Colab**.
- Algumas bibliotecas (como `spacy`) exigem a instalação de modelos adicionais. Exemplo:

```bash
python -m spacy download pt_core_news_sm
