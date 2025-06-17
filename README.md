# Segmentação HSV Interativa

Este projeto permite fazer segmentação de cores em imagens usando o espaço de cor HSV (Hue, Saturation, Value). A ideia é facilitar a identificação de faixas de cor específicas com a ajuda de sliders interativos, exibindo o resultado visualmente de forma prática.

## Como funciona

O usuário faz o upload de uma imagem diretamente no Google Colab. Em seguida, os sliders permitem ajustar os valores mínimos e máximos de matiz (H), saturação (S) e valor (V). A imagem original e a imagem filtrada são mostradas lado a lado para facilitar a comparação e análise.

## Tecnologias e bibliotecas utilizadas

- OpenCV (`cv2`) – leitura, conversão e manipulação de imagens
- NumPy – tratamento de arrays e máscaras
- Matplotlib – exibição de imagens
- Ipywidgets – sliders interativos
- IPython.display – integração dos widgets no notebook
- Google Colab – execução do notebook com suporte ao upload de arquivos

## Como usar

1. Abra o notebook no Google Colab.
2. Execute a célula principal.
3. Faça o upload de uma imagem quando solicitado.
4. Use os sliders para ajustar os valores de HSV e visualizar a filtragem em tempo real.

## Observações

- O notebook foi pensado para rodar no ambiente do Google Colab, que já possui suporte ao upload de arquivos e aos widgets interativos.
- O espaço de cor HSV é útil para separar características de cor mais facilmente do que o RGB, principalmente em aplicações de visão computacional.

## Autor

Desenvolvido por Allyson Túlio como parte dos estudos em visão computacional com Python.
