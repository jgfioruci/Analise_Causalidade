# **Análise Descritiva de Dados – Banco de Dados FOSP**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge\&logo=python\&logoColor=white)

Este projeto realiza uma **análise descritiva** sobre as variáveis do **banco de dados da FOSP (Fundação Oncocentro de São Paulo)**, com o objetivo de extrair insights iniciais e preparar dados para futuras inferências.

---

## 📋 Sumário

* [Sobre o Projeto](#sobre-o-projeto)
* [Conteúdo](#conteúdo)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Estrutura de Diretórios](#estrutura-de-diretórios)
* [Como Reproduzir](#como-reproduzir)
* [Autores](#autores)

---

## 📝 Sobre o Projeto

A análise descritiva tem foco em:

* **Limpeza e tratamento de dados** (valores faltantes, duplicatas)
* **Estatísticas univariadas** (média, mediana, quartis)
* **Visualizações exploratórias** (histogramas, boxplots, scatterplots)
* **Análise de correlação** entre variáveis-chave
* Identificação de padrões e outliers

O notebook principal [`Análise Descritiva.ipynb`](notebooks/Análise%20Descritiva.ipynb) contém todo o fluxo de trabalho, desde a importação até a geração de gráficos e tabelas resumo.

---

## 🚀 Conteúdo

* `data/raw/` – Dados originais sem tratamento
* `data/processed/` – Conjuntos preparados para análise
* `notebooks/Análise Descritiva.ipynb` – Notebook Jupyter com etapas e visualizações
* `src/` – Scripts Python modulados para limpeza e geração de relatórios
* `requirements.txt` – Dependências do projeto

---

## 🛠 Tecnologias Utilizadas

* **Python 3.10+**
* **pandas** – Manipulação e transformação de dados
* **NumPy** – Operações numéricas
* **Matplotlib** – Gráficos estáticos
* **Seaborn** – Visualizações estatísticas
* **Jupyter Notebook** – Ambiente interativo

---

## 💻 Como Reproduzir

1. **Clone o repositório**

   ```bash
   git clone https://github.com/jgfioruci/Analise_Causalidade.git
   cd Analise_Causalidade
   ```
2. **Crie e ative um ambiente virtual**

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate    # Windows
   ```
3. **Instale as dependências**

   ```bash
   pip install -r requirements.txt
   ```
4. **Abra e execute o notebook**

   ```bash
   jupyter notebook
   ```

   Em seguida, escolha `notebooks/Análise Descritiva.ipynb` e siga as células em ordem.

---

## 👥 Autores

* João Gabriel Fioruci
* Vaderlei Parro
* Lucas Buk Cardoso

*Qualquer dúvida ou sugestão, abra uma issue ou envie um pull request!*
