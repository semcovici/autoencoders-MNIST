# Comparação: AE, DAE e VAE

Este projeto explora a aplicação e comparação entre diferentes arquiteturas de autoencoders: Autoencoder simples (AE), Autoencoder Denoising (DAE) e Variational Autoencoder (VAE), utilizando o dataset FashionMNIST como base.

## Estrutura do Projeto

```
.
├── enunciado
│   └── ep4.pdf                # Enunciado do projeto
├── notebooks
│   ├── base # arquivos utilizados como inspiração
│   │   ├── EP4-VAE.html       # Exportação em HTML do notebook VAE
│   │   └── EP4-VAE.ipynb      # Notebook base para estudo do VAE
│   ├── data
│   │   └── FashionMNIST
│   │       └── raw            # Dados brutos do FashionMNIST (gerados ao rodar notebook)
│   └── exploracao.ipynb       # Notebook principal do projeto
├── README.md                  # Este arquivo
└── requirements.txt           # Dependências do projeto
```

## Notebook Principal

O foco principal do projeto é o notebook `exploracao.ipynb`, que contém a implementação e análise das diferentes arquiteturas (AE, DAE e VAE) aplicadas ao dataset FashionMNIST. Nele, você encontrará:

- Pré-processamento dos dados do FashionMNIST.
- Implementação das arquiteturas mencionadas.
- Comparação qualitativa e quantitativa dos resultados.

## Dependências

Para rodar o projeto, é necessário instalar as dependências listadas no arquivo `requirements.txt`. Utilize o seguinte comando:

```bash
pip install -r requirements.txt
```

## Como Executar

1. Certifique-se de ter instalado as dependências do projeto.
2. Abra o notebook principal `exploracao.ipynb` em um ambiente Jupyter.
3. Execute as células sequencialmente para replicar os resultados e análises.

## Informações Adicionais

O arquivo `enunciado/ep4.pdf` contém informações detalhadas sobre o objetivo e contexto do projeto. Os notebooks na pasta `notebooks/base` são os notebooks utilizados como base para a implementação.