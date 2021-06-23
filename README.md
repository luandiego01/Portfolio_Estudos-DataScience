# Portfolo de Estudos - DataScience

Nesse repositório coloquei alguns notebooks com exercícios relacionados a Data Science que venho fazendo durante meus estudos.

#### Obs.: Os exercícios não foram elaborados por mim, eu respondi eles para um curso que estou fazendo, a ideia é poder mostrar um pouco da minha evolução e aprendizado.

Os datasets utilizados que precisam ser baixados estão no repositório 'DatasetsEstudos'.

Os exercícios são:

__01 - Implementando_ML_do_zero:__

Nesse exercício o foco é na criação de modelos de machine learning do zero, usando fórmulas e algoritmos, usar esses modelos, para comparar com os modelos já existentes no SciKit Learn.

__02 - Modelos_de_árvores_e_emsemble:__

Nesse exercício, discutimos como encontrar melhores parâmetros para modelos de arvores e emsembles, criamos uma classe gridSeachall que faz essa busca por parâmetros, afim de encontrarmos os melhores modelos.

Também durante o exercício fazemos uma rapida análise exploratória nos dados para conseguir usar os modelos de uma maneira melhor.

__03 - Detecção_de_anomalias:__

Aqui nos estudamos como modelar e encontrar anomalias em um conjunto de dados, com o auxílio da gaussiana, o mais interessante nesse exercício é que intuitivamente podemos pensar no problema de anomalias como um problema de classificação, porém é muito difícil, quase impossível algum modelo de classificação conseguir detectar anomalias, pois a quantidade delas geralmente é muito pequena em um grande conjunto de dados.

Portanto, abordando no contexto de estatística sem nenhum modelo de Machine Learning, conseguimos detectar essas anomalias, de uma maneira bem precisa.

__04 - Sistema_de_recomendações:__

Nesse exercício, discutimos como encontrar melhores paramêtros para uma classe de fatoração criada afim de fazer recomendações de um catálogo de filmes para determinados usuários que ainda não assistiram todos os filmes.

__05 - Redes_Neurais_ferramentas:__

Nesse exercício eu mostros como algumas pequenas ferramentas do Keras podem melhorar significamente nossa rede neural, construo uma rede que inicialmente possui apenas 30% de acurácia e com algumas pequenas modificações, a acurácia aumenta para 50%.

__06 - Detecção_de_objetos:__

Nesse notebook, a ideia principal é usar duas ferramentas poderosas de maneira conjunta para detectar objetos em imagens, usamos o Selective Search do OpenCV e a VGG19 do Keras de maneira conjunta, o Selective search para recortar a imagem em diversas outras imagens selecionadas pelo algoritmo, e usar essas novas imagens no VGG19, afim de fazer a deteção do objeto da imagem de maneira eficaz.

__07 - Deep_Leaning_e_construção_de_imagens:

Aqui nos usamos a tecnica de autoencoder variacional e usamos um dataset com mais de 20 mil imagens de face para fazer que o algoritmo aprenda a construir faces, faces de todas as etnias, idades e gêneros. Treinamos o modelo por apenas 20 minutos em um computador pessoal e já foi suficiente para ele aprender a reconstruir faces muito bem feitas.
