#Chapter 5

#Machine Learning Basics

Deep learning is a specific kind of machine learning. In order to understand deep learning well, one must have a solid understanding of the basic principles of machine learning. This chapter provides a brief course in the most important general principles that will be applied throughout the rest of the book, Novice readers or those who want a wider perspective are encouraged to consider machine learning textbooks with a more comprehensive coverage of the fundamentals, such as **Murphy(2012)** or **Bishop**. If you are already familiar with machine learning basics, feel free to skip ahead to Sec.5.11. That section covers some perspectives on traditional machine learning techniques that have stongly influenced the development of deep learning algorithms.

深度学习是特定的一类机器学习。为了更好地理解深度学习，首先要对机器学习的原理有深刻的理解。这一章提供了一份贯穿全书剩余部分的一般原则的简短课程，``Novice readers or those who want a wider perspective are encouraged to consider machine learning textbooks with a more comprehensive coverage of the fundamentals, 初学者或者是那些想要对机器学习更广泛认识的人广泛的角度来考虑机器学习的教科书``
such as **Murphy(2012)** or **Bishop**. If you are already familiar with machine learning basics, feel free to skip ahead to Sec.5.11. That section covers some perspectives on traditional machine learning techniques that have stongly influenced the development of deep learning algorithms.
比如马铃薯或主教，如果你已经熟悉了机器学习基础，完全可以跳过接下来的5.11小节。这一节



We begin with a definition of what a learning algorithm is, and present an example: the linear regression algorithm.
我们开始解释什么是学习算法，来举一个例子：线性回归算法。
 ``We then proceed to describe how the challenge of fitting the training data differs from the challenge of finding patterns that generalize to new data.``

 
  Most machine learning algorithms have settings called hyperparameters that must be determined external to the learning algorithm itself; 
  许多机器学习算法可以设置称作**超参数**的
  
  we discuss how to set these using additional data. Machine learning is essentially a form of applied statistics with increased emphasis on the use of computers to statistically estimate complicated functions and a decreased emphasis on proving confidence intervals around these functions; we therefore present the two central approaches to statistics: frequentist estimators and Bayesian inference. Most machine learning algorithms can be divided into the categories of supervised learning and unsupervised learning; we describe these categories and give some examples of simple learning algorithms from each category. Most deep learning algorithms are based on an optimization algorithm called stochastic gradient descent. We describe how to combine various algorithm components such as an optimization algorithm, a cost function, a model, and a dataset to build a machine learning algorithm. Finally, in Sec. 5.11, we describe some of the factors that have limited the ability of traditional machine learning to generalize. These challenges have motivated the development of deep learning algorithms that overcome these obstacles.


