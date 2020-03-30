# People-Detection-Image-classification


Para o projeto usaremos a base de dados INRIA Person. Nela o objetivo é classificar imagens que possuam ou não pessoas.
O projeto principal é composto por um arquivo extracao_de_caracteristicas.ipynb. Neste possui toda a rotina de extração de características e classificação. É utilizado o algoritmo ORB para extração de descritores da imagem e estes descritores processados com o algoritmo Bag of Visual Words que gerará um dicionário de palavras e assim irá gerar novas caracteristicas a serem quantizadas em um vetor de 512 posições que será a base de dados para teste e treinamento do modelo.
Para classificação é utilizado KNN para classificar cada imagem se possui ou não pessoa na imagem e então é verificado a acurácia geral do modelo mostrando também a matriz de confusão para entendimento do problema.

Dados diponivíes em : <https://drive.google.com/open?id=1Ool67lKegNCFBqvQaEsUHqu3XWCC98R7>
