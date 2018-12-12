# momentForests
Java source code implementing moment forests from Asher, Nekipelov, Novosad, and Ryan (2018). 
See https://sites.wustl.edu/stephenpryan/files/2018/02/momentTrees-2m5z1ds.pdf.

## Use
```
mkdir bin
javac -d bin -sourcepath java/core -cp jars/Jama-1.0.3.jar:jars/commons-beanutils-1.9.3.jar:jars/commons-collections4-4.1.jar:jars/commons-io-2.6.jar:jars/itext-1.3.jar:jars/jcommon-1.0.23.jar:jars/jfreechart-1.0.19.jar:jars/jsci-core.jar:jars/optimization.jar:jars/pmUtility.jar:jars/readme.txt:jars/snappy-java-1.1.7.jar java/core/*.java
java -cp bin:jars/Jama-1.0.3.jar:jars/commons-beanutils-1.9.3.jar:jars/commons-collections4-4.1.jar:jars/commons-io-2.6.jar:jars/itext-1.3.jar:jars/jcommon-1.0.23.jar:jars/jfreechart-1.0.19.jar:jars/jsci-core.jar:jars/optimization.jar:jars/pmUtility.jar:jars/readme.txt:jars/snappy-java-1.1.7.jar core.DisjointSet
```

Original source: github.com/cactus911/momentForests. 
Copyright 2018 Stephen P. Ryan.
