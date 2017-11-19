# Kmeans
The first step of machine learning
# explain:
  According to analyse the last 4 times European Cup ranking of 16 countries, we could divide the football level of different countries<br>
  This program just clustered for 3 groups, the group name dont equal the football team ranking<br>
  <br>
  Group 1:England France<br>
  Group 2:Switzerland, Poland, Wales, Northern Ireland, Hungray, Belgium, Slovakia, Ireland and Iceland<br>
  Group 3:Portugal, German, Croatia, Italy and Spain<br>
The most surprising results is Croatia. Although Croatia is not storng as other group 3 countries, with smooth results it is better than England and France.<br>

# implement flow：
  1. read data in dataset<br>
  2. Randomly produce init-clusters<br>
  3. Calculate all spots of shortly distance to clusters, and reassign for 3 groups <br>
  4. updata the new cluster, and repeat step 3, until the position of clusters not change<br>
In step 2, program may produce invild clusters. For instance, the position beyond our examples(data). It could cause the error, so next step I would imporve it.<br>
  
#Reference:
https://www.coursera.org/learn/machine-learning/lecture/93VPG/k-means-algorithm <br>
http://www.cnblogs.com/leoo2sk/archive/2010/09/20/k-means.html  <br>
https://github.com/wepe/MachineLearning/tree/master/KMeans <br>
