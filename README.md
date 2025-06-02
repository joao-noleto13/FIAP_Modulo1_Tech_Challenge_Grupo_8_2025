
# FIAP_Modulo1_Tech_Challenge: Previsão de Custos Médicos com Regressão e Random Forest

## Descrição  
Este projeto tem como objetivo desenvolver um modelo preditivo para estimar os custos de seguros médicos com base em variáveis como idade, IMC, número de filhos, hábito de fumar e região. Foram aplicadas técnicas de regressão e ciência de dados para construção de modelos robustos e interpretáveis.

---

## Motivação  
Este desafio integra o módulo de aprendizado do curso de pós-graduação em Inteligência Artificial para Desenvolvedores, na FIAP. A proposta visa aplicar algoritmos de aprendizado supervisionado para resolver um problema prático e realista, alinhado ao contexto do setor de seguros e saúde. Além de exercitar conceitos estatísticos e computacionais, o projeto reforça a capacidade analítica ao interpretar os fatores que mais influenciam os custos médicos individuais.

---

## Tecnologias Utilizadas

- **Linguagem**: Python 3  
- **Bibliotecas**:
  - Pandas, NumPy – Manipulação e análise de dados
  - Matplotlib, Seaborn – Visualização de dados
  - Scikit-Learn – Modelagem e métricas de regressão
  - Statsmodels – Análise estatística
  - Kagglehub – Acesso direto ao dataset via API
- **Ambiente**: Google Colab

---

## Configuração e Execução

1. Acesse o [Google Colab](https://colab.research.google.com/)
2. Faça upload do arquivo `Custos_medicos_individuais.ipynb`
3. Execute as células do notebook sequencialmente para visualizar a análise, a modelagem e os resultados

---

## Dados

O conjunto de dados foi obtido a partir da plataforma Kaggle:

- [Health Insurance Data Set - Kaggle](https://www.kaggle.com/datasets/sureshgupta/health-insurance-data-set)

O dataset inclui variáveis como:

- Idade  
- Sexo  
- IMC (Índice de Massa Corporal)  
- Número de filhos  
- Hábito de fumar  
- Região  
- Custo do seguro médico  

Essas informações permitem avaliar com precisão os fatores que mais impactam nos custos dos planos de saúde.

---

## Resultados e Conclusões

Durante o desenvolvimento, foi possível identificar que as variáveis **tabagismo**, **IMC** e **idade** são as que mais influenciam o valor do seguro médico.

- O modelo **Random Forest Regressor** apresentou melhor desempenho em relação à Regressão Linear, capturando melhor as não-linearidades e interações entre variáveis.
- A análise estatística com p-values e intervalos de confiança trouxe maior confiabilidade para os resultados interpretativos do modelo linear.

As visualizações e métricas (R², MAE, MSE) reforçaram a qualidade do modelo final e a viabilidade da aplicação em contextos reais de seguros.

---

## Integrantes do Grupo

João Pedro Noleto – RA: 363789

Danilo Almeida de Sousa – RA: 362639

Allan dos Santos – RA: 362388

Thiago Silva França – RA: 361249

Emerson Luis Saturnino – RA: 362286 
