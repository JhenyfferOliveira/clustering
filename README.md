# 💳 Credit Card Customer Clustering

Projeto de segmentação de clientes de cartão de crédito utilizando técnicas de aprendizado não supervisionado.

---

## 🎯 Objetivo

Identificar perfis comportamentais de clientes a partir de dados de uso do cartão de crédito, gerando segmentos acionáveis para estratégias de negócio.

---

## 📦 Dataset

- **Fonte:** [Kaggle — Credit Card Customer Data](https://www.kaggle.com/datasets/aryashah2k/credit-card-customer-data)
- **Autor:** Arya Shah
- **Registros:** ~10.000 clientes
- **Features:** Dados demográficos + comportamento financeiro

---

## 🗂️ Estrutura
```
credit-card-clustering/
│
├── data/
│   └── CreditCardCustomerData.csv
│
├── notebook/
│   └── clustering.ipynb
│
├── requirements.txt
└── README.md
```

## 🔬 Metodologia

| Etapa | Descrição |
|---|---|
| **EDA** | Análise exploratória, distribuições e correlações |
| **Pré-processamento** | Limpeza, encoding, scaling e PCA |
| **Escolha do K** | Cotovelo, Silhueta, Davies-Bouldin, Calinski-Harabasz |
| **Clusterização** | K-Means + Clusterização Hierárquica |
| **Visualizações** | PCA 2D, Radar Chart, Heatmap, Boxplots, Pairplot |
| **Validação** | Kruskal-Wallis (numéricas) + Chi² (categóricas) |

---

## 📊 Resultados



---

## ▶️ Como executar

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/clustering.git
cd credit-card-clustering

# 2. Instale as dependências
pip install -r requirements.txt

# 3. Baixe o dataset no Kaggle e salve em /data

# 4. Execute o notebook
jupyter notebook notebook/clustering.ipynb