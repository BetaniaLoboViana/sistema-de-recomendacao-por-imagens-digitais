# Sistema de Recomendação por Imagens

Este projeto implementa um **Sistema de Recomendação por Imagens** que sugere produtos semelhantes com base na **similaridade visual**. O sistema usa **Deep Learning** para analisar as características visuais das imagens, como **formato, cor, textura** e **outros elementos visuais**.

O objetivo é ajudar o usuário a encontrar produtos similares com base nas imagens fornecidas.

## Funcionalidades

- **Extração de características de imagens**: Uso de redes neurais para extrair características visuais importantes de cada imagem.
- **Cálculo de similaridade**: Implementação de métricas de similaridade (como **cosine similarity**) para comparar imagens e identificar aquelas que são visualmente semelhantes.
- **Recomendações personalizadas**: O sistema recomenda as **top N imagens** mais semelhantes com base na imagem fornecida pelo usuário.


## Como Funciona

1. **Extração de características**: Para cada imagem fornecida, extraímos características visuais utilizando uma rede neural treinada.
2. **Cálculo de similaridade**: Calcula a similaridade entre a imagem fornecida e as imagens armazenadas no banco de dados.
3. **Recomendações**: As imagens mais semelhantes são selecionadas e apresentadas ao usuário.

## Requisitos

Para rodar este projeto, é necessário ter as seguintes dependências:

- Python 3.x
- TensorFlow ou PyTorch (para Deep Learning)
- Scikit-learn (para cálculos de similaridade)
- Matplotlib (para visualização de imagens)
- OpenCV (para manipulação de imagens)



