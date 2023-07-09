# nndl Neural Networks and Deep Learning

Material developed for [Texas A&M University -
Commerce](http://tamuc.edu) course CSci 560: Neural Networks and
Deeo Kearbubg.  These materials were initially developed in the
Spring of 2019 and 2020 semester.

## Content

- The main content of the course will be delievers as interactive
  ipython/Jupyter notebooks.  These iPython/Jupyter notebooks (which use extension .ipynb)
  can be found in the lectures subdirectory of the repository.
- All assignments for the course will appear in the assignments folder and/or will
  be posted through our universities online learning system (MyLeoOnline).



## More content

Suggested material for learning python:

- [Think Python: How to think like a computer scientist](http://www.greenteapress.com/thinkpython/) free online textbook, very good resource for not only Python but learning to program in general.
- [Google Developers Python Class](https://developers.google.com/edu/python/?hl=ru&csw=1) short course with videos, might be helpful for those looking for video tutorials of Python.
- [Software Carpentry](http://swcarpentry.github.io/python-novice-inflammation/) section on learning Python is also very good, and also includes videos.

Companion Textbooks on Neural Networks, Deep Learning and Machine Learning:

- Francois Chollet (2018). [Deep Learning with Python](https://www.amazon.com/Deep-Learning-Python-Francois-Chollet/dp/1617294438/ref=sr_1_3?keywords=deep+learning+with+python&qid=1578849718&sr=8-3). Manning.
- Aurelian Geron (2019). [Hands-On Machine Learning with SciKit-Learn and TensorFlow: Concepts, tools, and techniques to build intelligent systems 2ed](https://www.amazon.com/dp/1491962291?aaxitk=GJCjkzlTbRkN0mdMTxzqSg&pd_rd_i=1491962291&pf_rd_p=9420597b-7dad-4cbd-a28d-7d676ac67378&hsa_cr_id=8420444930901&sb-ci-n=productDescription&sb-ci-v=Hands-On%20Machine%20Learning%20with%20Scikit-Learn%20and%20TensorFlow%3A%20Concepts%2C%20Tools%2C%20and%20Techniques%20to%20Build%20Intelligent%20Systems&sb-ci-a=1491962291). O'Reilly Media.
- Michael Nielsen (2019). [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/).


## Getting Started

In the first day are two of the first week of class, you should try
and work on the Getting Started tasks mentioned in our MyLeoOnline
class.  You need to have a working system that you can run
Python/Jupyter notebooks on, and specifically that have scikit-learn,
Keras and maybe also Tensorflow Python libraries installed and
working.  You should try and set up such an environment on a personal
laptop or desktop computer that you have access to.  Here are links to
recent instructions for setting up Python Jupyter notebooks.  All of
them have instructions for using the Anaconda installer, which I
recommend for installing and managing the system on your personal
computer.

- [How to install Jupyter Notebook on Windows](https://www.geeksforgeeks.org/how-to-install-jupyter-notebook-in-windows/)
- [How to Install Jupyter Notebook on Mac and Windows](https://www.codecademy.com/article/setting-up-jupyter-notebook)

In addition, you may want to try using Google colab, which gives the
ability to create and run Jupyter notebooks, and has some limited free
access to gpu resources

- [Getting Started with Google Colab](https://colab.research.google.com/?utm_source=scs-index)

In addition, especially for training transformers and other genreative
deep learning models, large amount of GPU/TPU resources are very
useful for doing more serious work.  I am currently trying out the
following:

- [TPU Research Cloud](https://sites.research.google/trc/about/)

If you have a jupyter notebook environment on a personal machine, you
can clone this repository to get the lecture notebooks for this class by
performing (this assumes you already have git installed on your system).

```
$ git clone https://github.com/csci560-nndl/nndl
```

We may be adding or updating content to this repository frequently.
Cloning the repository using the https url means it is read only,
you cannot make changes and push those changes back to the class
repository.  So feel free to update the notebooks to try things
out.  If you need to pull down new content that was added
after you did the initial clone, simply perform a git update in
your repository directory

```
$ git update
```

