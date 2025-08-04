# Garbage Classification

Classificação automática de resíduos sólidos usando técnicas de visão computacional e aprendizado de máquina.

## Visão Geral

Esse projeto implementa um modelo de deep learning para identificar tipos de lixo em imagens, contribuindo para soluções de reciclagem automatizadas e descarte consciente.

## Funcionalidades

* Classificação de resíduos em categorias como: orgânico, reciclável, perigoso e geral
* Pipeline completo de treinamento e avaliação de modelos
* Suporte a visualização de métricas e resultados
* Estrutura modular e extensível

## Estrutura do Projeto

```
garbage-classification/
├── data/                           # Conjuntos de dados
├── models/                         # Pesos e checkpoints
├── utils/                          # Funções auxiliares
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


