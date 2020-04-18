### Introduction
* __Sources__:
    * In 2013, Google opened up word2vec, a tool for calculating word vectors
    * It is actually a tool for converting raw natural language into mathematical data, which can be processed by a computer
    * <a href='https://blog.csdn.net/u014595019/article/details/51884529'>Source code</a>
* __Scenarios__:
    * __CBoW__ is suitable for small-scale or corpora with relatively loose topics. After all, it's vector generation is only related to nearby words, and farther corpora are not used.
    * In contrast, __skip-gram__ can process a large number of corpora based on the same semantic and meaning groups