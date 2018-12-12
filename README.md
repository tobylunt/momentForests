# momentForests
Java source code implementing moment forests from Asher, Nekipelov, Novosad, and Ryan (2018). 

# The paper:

See https://sites.wustl.edu/stephenpryan/files/2018/02/momentTrees-2m5z1ds.pdf.

From the abstract:
>We propose a new methodology, moment forests, that allows parameters in a broad class of moment-based models to vary across groups of observations on the basis of observable characteristics. Leveraging a generalization of classification trees, the estimator first assigns observations to disjoint subgroups sharing common parameters, and then estimates an empirical model within each group. We prove the consistency of this estimator and show that standard rates of convergence apply to the second stage estimates under weak regularity conditions. We showcase our approach by estimating heterogeneous treatment effects in a regression discontinuity design in a development setting.

# Use
```
// need a directory for compiled binaries. be sure to add 
mkdir bin

// javac is our unix compiler. this step compiles our source files in /java/core, including our helper utilities in jars/.
javac -d bin -sourcepath java/core -cp jars/Jama-1.0.3.jar:jars/commons-beanutils-1.9.3.jar:jars/commons-collections4-4.1.jar:jars/commons-io-2.6.jar:jars/itext-1.3.jar:jars/jcommon-1.0.23.jar:jars/jfreechart-1.0.19.jar:jars/jsci-core.jar:jars/optimization.jar:jars/pmUtility.jar:jars/readme.txt:jars/snappy-java-1.1.7.jar java/core/*.java

// java executes a compiled source file - in this case DisjointSet in the core directory. again, jars also must be specified.
java -cp bin:jars/Jama-1.0.3.jar:jars/commons-beanutils-1.9.3.jar:jars/commons-collections4-4.1.jar:jars/commons-io-2.6.jar:jars/itext-1.3.jar:jars/jcommon-1.0.23.jar:jars/jfreechart-1.0.19.jar:jars/jsci-core.jar:jars/optimization.jar:jars/pmUtility.jar:jars/readme.txt:jars/snappy-java-1.1.7.jar core.DisjointSet
```

Original source: github.com/cactus911/momentForests. 
Copyright 2018 Stephen P. Ryan.
