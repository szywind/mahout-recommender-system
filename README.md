# A recommender system built on hadoop 2.x

Refer to [this repo](https://github.com/bsspirit/maven_mahout_template/tree/mahout-0.8) and make it work on hadoop 2.x.
This distributed recommender system is based on Mahout's built-in itemCF algorithm.

Run on hadoop:
```shell
hadoop jar myMahout.jar org.conan.mymahout.recommendation.ItemCFHadoop
```

Check the results:
```shell
hdfs dfs -cat /user/hdfs/userCF/result/part-r-00000
```
Reference:

[http://blog.fens.me/hadoop-mahout-mapreduce-itemcf/](http://blog.fens.me/hadoop-mahout-mapreduce-itemcf/)
