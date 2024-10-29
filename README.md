# Transfer Learning com Redes Neurais Convolucionais

Este projeto implementa **Transfer Learning** com uma rede neural convolucional (CNN) usando um modelo base pré-treinado para classificação de imagens. Utilizamos um modelo como o `MobileNetV2` ou `VGG16`, e aplicamos técnicas de **fine-tuning** para ajustar o modelo ao nosso conjunto de dados específico.

## Estrutura do Projeto

- **Transfer_Learning.ipynb**: O notebook principal com todo o código para carregar o modelo, ajustar as camadas finais e treinar o modelo no conjunto de dados.
- **datasets/**: (Opcional) Diretório para armazenamento de dados de imagem.
- **models/**: (Opcional) Diretório para salvar o modelo treinado.

## Funcionalidades

- **Transferência de Aprendizado**: Utiliza um modelo pré-treinado para extrair características de alto nível, reduzindo a quantidade de dados e tempo necessários para o treinamento.
- **Fine-Tuning**: Ajusta as camadas finais da rede para melhorar a capacidade de generalização do modelo.
- **Classificação de Imagens**: Adapta a rede convolucional para realizar classificação com base em um conjunto de dados específico.

## Tecnologias Utilizadas

- **Python** (3.x)
- **TensorFlow** e **Keras**: Para criação e treinamento de redes neurais.
- **Jupyter Notebook**: Para implementação e execução do código.

## Configuração

### Dependências

- `tensorflow`
- `numpy`
- `matplotlib` (opcional, para visualização de gráficos)

Instale as dependências com:

```bash
pip install tensorflow numpy matplotlib
