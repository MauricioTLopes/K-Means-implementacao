# K-Means-implementacao
Implementação do algortimo K-means para a cadeira de Inteligencia Computacional

PERGUNTA

QUAL A INFLUÊNCIA DOS ELEMENTOS INICIAIS NA FORMAÇÃO DOS GRUPOS NO KMEANS?


Os centróides iniciais são formados através da designação de cada caso ao cluster de centro
mais próximo. Com a inclusão de cada caso, a média altera-se, alterando assim o centróide.
Um processo iterativo é usado para achar os centróides finais de cada cluster. A cada passo,
os casos são agrupados ao cluster de centro mais próximo, e novamente as médias são
recalculadas. Este processo continua até que não haja mais alterações nas médias ou que um
número pré-determinado de iterações aconteça, encerrando-se o processo
