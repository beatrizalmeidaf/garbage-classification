# Garbage Classification

Classificação automática de resíduos sólidos usando técnicas de visão computacional e aprendizado de máquina.

> ⚠️ **Nota:** Esse é um projeto básico criado com o objetivo de fortalecer alguns entendimentos sobre visão computacional. Utiliza um dataset disponível no Kaggle e **não possui uma estruturação robusta ou foco em produção**, sendo voltado apenas a fins exploratórios.

## Visão Geral

Esse projeto implementa um modelo de deep learning para identificar tipos de lixo em imagens, contribuindo para soluções de reciclagem automatizadas e descarte consciente.

## Funcionalidades

* Classificação de resíduos em categorias
* Pipeline de treinamento e avaliação de modelos
* Suporte a visualização de métricas e resultados

## Estrutura do Projeto

```
garbage-classification/
├── data/                           # Conjuntos de dados                       
├── garbage-classification.ipynb    # Arquivo principal
├── requirements.txt                # Dependências
└── README.md
```

## Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/beatrizalmeidaf/garbage-classification.git
cd garbage-classification
```

2. Crie o ambiente virtual e instale as dependências:

```bash
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
```

3. Execute o notebook:

```bash
jupyter notebook garbage-classification.ipynb
```

## Resultados

* Acurácia de validação: **98.81%%**
* Precisão média: **98.40%**
* Recall médio: **98.94%**


