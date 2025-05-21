# Análise de Agrupamento com K-Means

Este projeto aplica o algoritmo de clusterização **K-Means** a uma base de dados de empresas brasileiras, com o objetivo de:

- Agrupar empresas por similaridade de perfil
- Identificar padrões de capital social e idade
- Apoiar análises exploratórias e segmentações para BI

## 📁 Estrutura

- `K-MEAN_ANALISE_COMPLETA.ipynb`: notebook principal com análise passo a passo
- `empresas_clusterizadas.parquet`: base de dados usada na análise


## 📊 Tecnologias Utilizadas

- Python 3.10+
- pandas, scikit-learn, matplotlib, seaborn, plotly
- Jupyter Notebook

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/jopezx/KMEAN.git
cd KMEAN
```

2. Crie e ative um ambiente virtual:
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate   # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Execute o notebook no Jupyter:
```bash
jupyter notebook
```

## 📌 Observações

- Certifique-se de ter o `kaleido` instalado para renderizar gráficos Plotly em PNG.
- Os dados usados são públicos e anonimizados.

## 📄 Licença

MIT - sinta-se livre para usar e adaptar.
