# 📊 Análise de Viagens - Portal da Transparência 2024

## 📌 Descrição
Este repositório contém a análise dos dados de viagens oficiais registradas no Portal da Transparência em 2024, com base no arquivo `2024_Viagem.csv`.  
A análise foi realizada utilizando **Python** (com bibliotecas como *Pandas* e *Matplotlib*) e **Jupyter Notebooks**, explorando padrões de despesas, duração das viagens, destinos e impactos de fatores como urgência.  

O projeto inclui um **relatório detalhado em Markdown** e **visualizações gráficas** geradas a partir dos dados.

---

## 🧭 Origem do Projeto
A primeira parte deste projeto foi desenvolvida acompanhando o curso **Python para Dados: do Zero à Análise Completa** da **Asimov**, servindo como base para a manipulação e visualização dos dados.  
As conclusões e os insights apresentados foram elaborados por mim, com base na interpretação dos resultados e na identificação de padrões e anomalias nos dados.

---

## 📦 Pré-requisitos

- Python 3.7 ou superior  
- Git (para clonar o repositório)  
- Bibliotecas listadas em `requirements.txt`

---

## 🚀 Como Usar

### 1. Baixe os Dados
Os dados do Portal da Transparência são grandes e **não estão incluídos diretamente** neste repositório. Para obtê-los:

- Acesse o [Portal da Transparência](https://www.portaltransparencia.gov.br/)
- Ou baixe diretamente os arquivos usados nesta análise:
  - `2024_Pagamento.csv`
  - `2024_Passagem.csv`
  - `2024_Trecho.csv`
  - `2024_Viagem.csv`

### 2. Configure o Ambiente Virtual

Crie e ative um ambiente virtual:

```bash
python -m venv .venv
```

# Ativação no Windows
.venv\Scripts\activate

# Ativação no Linux/Mac
source .venv/bin/activate

## Instale as dependências:

pip install -r requirements.txt

### 3. Explore o Projeto

- Abra o relatório completo em relatorio.md usando um visualizador de Markdown (ex.: VS Code, GitHub).

- Verifique as imagens geradas na pasta images/ (ex.: despesas_totais_por_cargo.png, boxplot_duracao.png).

- (Opcional) Se houver notebooks na pasta notebooks/, abra-os no Jupyter Notebook ou JupyterLab para reproduzir a análise.

--- 
## 🗂 Estrutura do Repositório

```bash
2024_Viagem.csv        # Arquivo de dados brutos utilizado na análise (deve ser baixado)
images/                # Pasta contendo as imagens geradas
relatorio.md           # Relatório completo em Markdown com análises e visualizações
requirements.txt       # Lista de dependências Python necessárias
notebooks/             # (Opcional) Jupyter Notebooks usados na análise
```

## 🤝 Contribuições
- Base: Curso Python para Dados: do Zero à Análise Completa (Asimov)

- Insights: Desenvolvidos por mim com base nos dados analisados
