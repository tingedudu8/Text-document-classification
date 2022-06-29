# Text-document-classification
Implementing a kNN classiﬁer to classify text documents. The implementation is in Python, on top of Spark.

## Categories
![这是图片](/images/Dataset.png)

The data set has 19,997 posts from 20 different categories.

## SparkCode
To count Top K most frequently occurring words in a text file.
![这是图片](/images/Spark.png)



## Achievement

### Result1:
![这是图片](/images/Result1.png)



Converts each of those 19,997 count vectors to TF-IDF vectors.

### Result2:
![这是图片](/images/Result2.png)



Build a kNN classiﬁer, embodied by the Python function predictLabel. This function will take as input a text string and a number k, and then output the name of one of the 20 newsgroups. This name is the newsgroup that the classiﬁer thinks that the text string is “closest” to.
### Result3:

![这是图片](/images/Result3.png)

