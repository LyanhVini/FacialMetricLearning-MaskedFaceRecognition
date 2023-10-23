# Reconhecimento Facial com Aprendizado de Métrica

Este projeto aborda um dos desafios contemporâneos no campo do Machine Learning: o reconhecimento facial eficaz para uma ampla variedade de pessoas. Tradicionalmente, o reconhecimento facial era tratado como um problema de classificação, onde cada indivíduo era considerado uma classe distinta. No entanto, esse método apresentava uma limitação significativa: a necessidade de re-treinamento do modelo sempre que uma nova pessoa era adicionada ao banco de dados, tornando a escalabilidade um desafio complexo.

Para superar essa limitação, este projeto se concentra no Aprendizado de Métrica (Metric Learning), uma abordagem do campo do Deep Learning. Em vez de classificar indivíduos, treinamos modelos para aprender uma métrica de distância entre entidades, gerando um vetor descritor exclusivo para cada pessoa. Esse vetor descreve as características distintivas de seus rostos, permitindo a inclusão de novas pessoas no banco de dados sem a necessidade de re-treinamento do modelo.

Neste projeto, você enfrentará o desafio de:

1. Treinar uma rede neural em um conjunto de dados que apresenta uma ampla variedade de celebridades.
2. Criar um banco de dados com imagens das celebridades, utilizando a saída do vetor descritor gerado pelo seu modelo.
3. Incluir uma nova pessoa no banco de dados após o treinamento da rede neural.
4. Realizar o reconhecimento facial de uma imagem dessa nova pessoa, usando-a com uma máscara facial.

- (link da base de dados)[https://drive.google.com/file/d/1Mrx0OKnBFteOw1q8IZy-n8x9q8cxZwhT/view] - `base de dados utilizada`
