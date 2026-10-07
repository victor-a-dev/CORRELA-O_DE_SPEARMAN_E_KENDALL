# Análise de Correlação: Idade vs. Frequência Cardíaca Máxima

Este projeto contém um script em Python para realizar uma análise exploratória e estatística utilizando o famoso dataset de Doença Cardíaca da UCI (Cleveland). O foco principal é investigar a relação entre a **idade** (`age`) dos pacientes e a **frequência cardíaca máxima alcançada** (`thalach`).

---

## 📊 Sobre o Projeto

O script realiza o fluxo completo de ciência de dados utilizando bibliotecas padrão do ecossistema Python:
1. **Aquisição de Dados:** Carrega automaticamente o dataset a partir do repositório oficial da UCI.
2. **Tratamento de Dados:** Identifica e remove valores ausentes (tratados originalmente com interrogações `?`) para garantir a integridade da análise.
3. **Análise Exploratória e Visualização:** Gera gráficos de distribuição (histogramas com curvas KDE) para examinar o comportamento das variáveis de idade e frequência cardíaca máxima.

---

## 🛠️ Tecnologias Utilizadas

As principais bibliotecas utilizadas neste projeto são:
* **Python**
* **Pandas** (Manipulação e limpeza de dados)
* **NumPy** (Operações numéricas)
* **SciPy** (Análise estatística)
* **Matplotlib** & **Seaborn** (Visualização de dados)

---

## 🚀 Como Executar

Você pode executar este código diretamente em um ambiente de notebooks compatível, como o **Google Colab**:

1. Copie o código Python do notebook.
2. Cole em uma nova célula do Google Colab ou Jupyter Notebook.
3. Execute as células em sequência para baixar os dados, realizar a limpeza e visualizar os gráficos gerados.

---

## 📈 Exemplo de Análise Realizada

O código limpa o DataFrame original (removendo registros com dados faltantes, passando de 303 para 297 instâncias válidas) e plota distribuições estatísticas para entender o perfil da amostra e como a frequência cardíaca máxima se comporta em relação à idade dos pacientes.