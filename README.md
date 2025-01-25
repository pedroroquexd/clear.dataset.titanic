# Projeto de Análise e Limpeza de Dados - Dataset Titanic

Este projeto tem como objetivo realizar a limpeza e análise exploratória dos dados do famoso dataset do Titanic, fornecendo insights valiosos sobre os passageiros a bordo.

## 📂 Sobre o Dataset

O conjunto de dados do Titanic contém informações sobre os passageiros do navio RMS Titanic, incluindo detalhes pessoais, condições de viagem e status de sobrevivência.

### 🔍 Variáveis disponíveis no dataset:

- **Survival**: Sobrevivência (0 = Não, 1 = Sim)
- **Pclass**: Classe do bilhete (1ª, 2ª e 3ª classes)
- **Sex**: Gênero do passageiro
- **Age**: Idade em anos
- **SibSp**: Número de irmãos/cônjuges a bordo do Titanic
- **Parch**: Número de pais/filhos a bordo do Titanic
- **Ticket**: Número do bilhete
- **Fare**: Tarifa paga pelo passageiro
- **Cabin**: Número da cabine
- **Embarked**: Porto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🛠️ Tecnologias utilizadas

- **Python** – Para manipulação e análise dos dados
- **Pandas** – Para tratamento de dados e geração de visualizações simples

## 🚀 Etapas do projeto

1. **Importação dos dados:** Carregar o dataset para análise.
2. **Análise exploratória (EDA):**
   - Criação de boxplots para identificar outliers.
   - Análise de histogramas para entender distribuições.
   - Uso de `groupby` para sumarizar os dados por categorias.
3. **Tratamento de dados faltantes:**
   - Uso de `fillna` para preenchimento de valores ausentes.
   - Exclusão de registros irrelevantes com `drop`.
4. **Cálculo de estatísticas descritivas:**
   - Determinação da mediana para variáveis numéricas relevantes.
5. **Transformação de dados:** Aplicação de funções com `transform` para ajustes e normalizações.
6. **Visualização de dados:**
   - Análise gráfica com `plot.hist` e boxplots.
7. **Conclusões finais:** Resumo das descobertas e próximos passos.

## 📊 Insights esperados

- Fatores que influenciaram a sobrevivência dos passageiros.
- Distribuição demográfica dos passageiros por classe.
- Análise das tarifas e sua relação com classes e portos de embarque.
