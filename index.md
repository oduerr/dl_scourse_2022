
# Deep Learning (Short)
## Short Course in Deep Learning given in fall 2022 at STUTS, Taiwan 

This course in deep learning focuses on practical aspects of deep learning. We therefore use jupyter notebooks, in the course. 

For doing the hands-on part, we recommend to use colab (you might need a google account) an internet connections is needed. If you want to do it without internet connection on your own computer you can either install anaconda ([details and installation instruction](anaconda.md)) or use the provided docker container ([details and installation instruction](docker.md)).

Please make sure that we can one the following notebook before the course:
* If colab check if the following link works and that you can execute the code  [https://colab.research.google.com/github/oduerr/dl_scourse_2022/blob/main/notebooks/00_Checking_Correct_Installation.ipynb](https://colab.research.google.com/github/oduerr/dl_scourse_2022/blob/main/notebooks/00_Checking_Correct_Installation.ipynb)
* If you use anaconda or docker check that you can execute the notebook `00_Checking_Correct_Installation` in [https://github.com/oduerr/dl_scourse_2022/notebooks](https://github.com/oduerr/dl_scourse_2022/tree/main/notebooks)

To easily follow the course please make sure that you are familiar with the some [basic math and python skills](prerequistites.md). 

## Info for the projects
You can join together in small groups (maximum 3 students) and choose a topic for your DL project. You should prepare a poster and a spotlight talk (5 minutes) which you will present on the last course day. The poster does not need to be fancy, a few printed out pages are fine too.

## Other resources 
This course a short version of a course designed and given together with Beate Sick for a continious education course in deep learning at the ZHAW in Winterthur (8 times 4 hours) [link](https://github.com/tensorchiefs/dl_course_2022). Other resources are:

* A version of the deep learning course with R (instead of python) given together we Beate Sick for a continious education course in deep learning at the ETH Zurich [link](https://github.com/tensorchiefs/dl_rcourse_2022). 

* Probabilistic Deep Learning (DL-Book) [Probabilistic Deep Learning](https://www.manning.com/books/probabilistic-deep-learning?a_aid=probabilistic_deep_learning&a_bid=78e55885). This book is by the Beate, Elvis, and Oliver (the [tensorchiefs](https://github.com/tensorchiefs)) and covers the increasingly popular probabilistic approach to deep learning.

* Deep Learning Book (DL-Book) [http://www.deeplearningbook.org/](http://www.deeplearningbook.org/). This is a quite comprehensive book which goes far beyond the scope of this course. 

* Convolutional Neural Networks for Visual Recognition [http://cs231n.stanford.edu/](http://cs231n.stanford.edu/), has additional material and [youtube videos of the lectures](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC). While the focus is on computer vision, it also treats other topics such as optimization, backpropagation and RNNs. Lecture notes can be found at [http://cs231n.github.io/](http://cs231n.github.io/).

* More TensorFlow examples can be found at [dl_tutorial](https://github.com/oduerr/dl_tutorial/tree/master/tensorflow/) 

* Another applied course in DL: [TensorFlow and Deep Learning without a PhD](https://cloud.google.com/blog/big-data/2017/01/learn-tensorflow-and-deep-learning-without-a-phd)

## Dates 
The course is structured in 4 sessions (blocks) and a presentation, each is 4 hourse long. Sometimes a session is lectured on two different days. 
### Week 1 (12 h / 3 Sessions)
* Mon  7 Nov 15:50-17:40 (2h) Session 1 (first half)
* Tue  8 Nov 12:50-14:40 (2h) Session 1 (second half)
* Wed  9 Nov 12:50-16:40 (4h) Session 2
* Thu 10 Nov 14:40-17:40 (4h) Session 3

### Week 2 (4 h / 1 Session and Presentation)
* Mon 14 Nov 15:50-17:40 (2h) Session 4 (first half)
* Tue 15 Nov 12:50-14:40 (2h) Session 4 (second half)
* Thu 15 Nov 12:50-14:40 (2h) Presentation


## Syllabus (might change during course).
### Session 1 (Introduction, Fully Connected Networks, Keras) 
* Slides [01_Introduction.pdf](https://github.com/oduerr/dl_scourse_2022/blob/master/slides/01_Introduction.pdf)
	* AI, Deeplearing
	* First Network (untrained and with numpy)
	* Hidden Layers for non-linear decision boundaries
	* Loss functions and simple networks for classification (softmax and categorical cross entropy)
	* Gradient Descent
	* Keras  
* [Notebooks](https://github.com/oduerr/dl_scourse_2022/tree/main/notebooks): 
  * 01_simple_forward_pass
  * 02_fcnn_with_banknote 

### Session 2 (Convolutional neural networks)
* Slides [02_fcNN_CNN.pdf](https://github.com/oduerr/dl_scourse_2022/blob/master/slides/02_fcNN_CNN.pdf)
* [Notebooks](https://github.com/oduerr/dl_scourse_2022/tree/main/notebooks): 
	* 03_fcnn_mnist (compare different models, relu)
	* 04_fcnn_mnist_shuffled 
	* 05_cnn_edge_lover (principle idea of convolutions)
	* 06_cnn_mnist_shuffled (a first complete CNN, effect of shuffeling)

### Session 3 (Tricks of the trade / sequence data)

The notebooks can be found at
* [https://github.com/oduerr/dl_scourse_2022/notebooks](https://github.com/oduerr/dl_scourse_2022/tree/main/notebooks). 

If you work with a local installation and know how to use github, you might want to check-out (or fork) the complete github repositoty [https://github.com/oduerr/dl_scourse_2022/](https://github.com/oduerr/dl_scourse_2022/). If you use colab and chrome, you might want to check out the "Open in Colab" extension. 





