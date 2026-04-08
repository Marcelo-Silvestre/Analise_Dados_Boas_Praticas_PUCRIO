# Analise_Dados_Boas_Praticas_PUCRIO
Repositório publico contendo o MVP da Disciplina Análise de Dados e Boas Práticas da Pós-graduação em Ciência de Dados &amp; Analytics PUCRIO 2025-2026

# MVP - Análise Descritiva de Ocorrências Criminais no Brasil (2015–2022)

**Autor:** Marcelo Alexandre Machado Silvestre

**Matrícula:** 4052025001857

**Curso:** Pós-Graduação em Ciência de Dados e Analytics – PUC-Rio

**Sprint:** Análise de Dados e Boas Práticas

---

## 1. Objetivo

Realizar uma análise exploratória dos dados de ocorrências criminais no Brasil entre 2015 e 2022, incorporando a padronização por população para permitir comparações consistentes entre unidades federativas.

---

## 2. Hipóteses

As hipóteses consideradas neste MVP são:

1. Estados mais populosos não necessariamente apresentam as maiores taxas de criminalidade.  
2. A padronização por população altera significativamente a interpretação dos resultados.  
3. Existem diferenças temporais relevantes na evolução dos crimes.  
4. Há diferenças regionais importantes nos padrões de criminalidade.  
5. Alguns tipos de crime apresentam maior volatilidade que outros.  

---

## 3. Bases de Dados

### Ocorrências Criminais (SINESP)
- UF  
- Tipo de Crime  
- Ano  
- Mês  
- Ocorrências  

### População (IBGE)
- UF  
- Ano  
- População  

---

##  4. Etapas do Projeto

### 4.1 Seleção e Carga de Dados  
Nesta etapa, foi realizada a importação das bibliotecas e o carregamento das bases de dados.  
Foi verificado o correto carregamento e a estrutura inicial dos datasets.

---

### 4.2 Análise Exploratória 
Nesta etapa, foi realizada a análise estrutural, estatísticas descritivas, histogramas, boxplots e matriz de correlação.  
Foi verificado o comportamento das distribuições, presença de valores nulos e existência de outliers.

---

### 4.3 Pré-processamento  
Nesta etapa, foi realizado o tratamento de valores nulos, padronização dos dados, integração das bases e criação da variável TX_100MIL.  
Foi verificada a consistência dos dados e a correta aplicação da normalização por população.

---

### 4.4 Transformações  
Nesta etapa, foi realizado o agrupamento dos dados, cálculo de métricas agregadas e criação de variáveis derivadas, incluindo análise de tendência.  
Foi verificada a coerência dos dados agregados e a consistência das transformações aplicadas.

---

### 4.5 Análise de Resultados  
Nesta etapa, foi realizada a comparação entre valores absolutos e taxas, análise temporal, análise regional e avaliação por tipo de crime.  
Foi verificado o impacto da normalização, diferenças entre regiões e padrões distintos entre categorias de crime.

---

##  5. Resultados das Hipóteses

### 5.1 Hipótese 1  
**Resultado:** Confirmada  
Estados mais populosos lideram em volume absoluto, mas não necessariamente em taxa.

---

### 5.2 Hipótese 2  
**Resultado:** Confirmada  
A normalização por população altera significativamente a interpretação dos dados.

---

### 5.3 Hipótese 3  
**Resultado:** Confirmada  
Há variações relevantes no comportamento dos crimes ao longo do tempo.

---

### 5.4 Hipótese 4  
**Resultado:** Confirmada  
Existem diferenças regionais importantes nos padrões de criminalidade.

---

### 5.5 Hipótese 5  
**Resultado:** Parcialmente confirmada  
Alguns crimes apresentam maior variabilidade, porém sem métrica formal de volatilidade.

---

##  6. Principais Insights

- A análise por taxa é mais adequada que valores absolutos  
- A normalização por população é essencial para comparações justas  
- Existem diferenças regionais consistentes  
- O comportamento dos crimes varia ao longo do tempo  
- Há diferenças de variabilidade entre tipos de crime  

---

##  7. Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  

---

##  8. Estrutura do Repositório
├── Arquivos/

├── Notebooks/

├── README.md

---

## 9. Limitações

- Não utilização de variáveis socioeconômicas  
- Ausência de modelagem preditiva  
- Dependência da qualidade dos dados públicos  

---

## 10. Trabalhos Futuros

- Aplicação de modelos de regressão  
- Clusterização de estados  
- Inclusão de variáveis externas  
