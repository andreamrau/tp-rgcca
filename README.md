# Introduction à l'analyse multi-blocs : RGCCA

*Présentations et codes reproductibles présentés lors de la journée StatOmique du 13 juin 2016*

-----------

## Pré-requis

Le langage que nous allons utiliser pour travailler sur l'analyse multi-blocs sera le langage R

 - Avant toutes choses, il faut donc installer le logiciel [R](https://cran.r-project.org/).
 - Puis pour pouvoir lire confortablement le code reproductible ainsi que le code R Markdown ayant servi à générer les présentations, il est fortement recommandé d'installer [RStudio](https://www.rstudio.com/).

RGCCA est disponible sous la forme d'un package R et s'installe par exemple de la façon suivante:

```
install.packages("RGCCA")
```

L'exemple que nous allons étudier pendant le TP est disponible sous la forme d'un package de données qui peut s'installer ainsi:

```
install.packages("http://biodev.cea.fr/sgcca/gliomaData_0.4.tar.gz", repos=NULL, type="source")
```

