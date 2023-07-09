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

- Michael Nielsen (2019). [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/).

- Aurelian Geron (2017). [Hands-On Machine Learning with SciKit-Learn and TensorFlow: Concepts, tools, and techniques to build intelligent systems](https://www.amazon.com/dp/1491962291?aaxitk=GJCjkzlTbRkN0mdMTxzqSg&pd_rd_i=1491962291&pf_rd_p=9420597b-7dad-4cbd-a28d-7d676ac67378&hsa_cr_id=8420444930901&sb-ci-n=productDescription&sb-ci-v=Hands-On%20Machine%20Learning%20with%20Scikit-Learn%20and%20TensorFlow%3A%20Concepts%2C%20Tools%2C%20and%20Techniques%20to%20Build%20Intelligent%20Systems&sb-ci-a=1491962291). O'Reilly Media.

- Segaran. (2007). [Programming Collective Intelligence](http://www.amazon.com/Programming-Collective-Intelligence-Building-Applications/dp/0596529325/ref=sr_1_1?ie=UTF8&qid=1376624477&sr=8-1&keywords=segaran+programming+collective+intelligence).
  Already 12 years old, so a bit out of date, and as far as I know no new
  editions.  But I will develop some of my optimization and decision
  tree examples from here.   [Code examples](https://github.com/uolter/PCI)

- Marsland. (2009). [Machine Learning: An Algorithmic Perspective](http://www.amazon.com/Machine-Learning-Algorithmic-Perspective-Recognition/dp/1420067184/ref=sr_1_1?ie=UTF8&qid=1376624555&sr=8-1&keywords=machine+learning+an+algorithmic+perspective).
  More examples of Python ML.  [Code examples](http://seat.massey.ac.nz/personal/s.r.marsland/MLbook.html)

- Conway & White. (2012).
  [Machine Learning for Hackers](http://www.amazon.com/Machine-Learning-Hackers-Drew-Conway/dp/1449303714/ref=sr_1_1?ie=UTF8&qid=1376624747&sr=8-1&keywords=machine+learning+for+hackers). [github repo of book source and data](https://github.com/johnmyleswhite/ML_for_Hackers)
  Case studies for this book are written in R.  This site
  [Will it Python](http://slendermeans.org/pages/will-it-python.html)
  has example reimplementations in iPython notebooks.



## Getting Started

Before the end of the first week of class, you need to get a working
Python distribution installed on your personal machine, and you need
to clone a copy of our class repository.  The following video should
help you in getting started:
[Getting Started](http://derekharter.com/class/videos/jupyter-git-setup-250.webm)

In order to do the class lectures and readings, you need to be able to
run and execute Jupyter notebooks.  In general, you need to complete
the following 4 steps.

1. Download and install a Python Distribution, such as Anaconda or
   Enthought python distributions, that includes support for Jupyter
   notebooks.
2. Download and install a git client on your machine.
3. Clone the class repository.
4. Test out Python, running Jupyter notebooks, and that you can access
   and execute the course lecture notebooks with your system setup.

### Download and Install a Python Distribution

For this course we recommend using a Python scientific distribution.
We recommend using the Anaconda distribution, though the Enthought
Canopy distribution should be fine as well.

- [Anaconda Distribution Download](https://www.anaconda.com/download/)
- [Enthought Canopy Distribution Download](https://store.enthought.com/downloads/)

Whether you are using Windows, Mac or Linux, the linked to installers
should work for you.  We are using Python version 3.x for this class,
so please download and install the 3.x version of the installer.  Python
2.x actually will probably work fine, but all of the libraries and code
we are using have been successfully moved over to Python 3, so you should
use version 3 of Python if at all possible.

### Download and Install Git Client

For Linux or Mac users, if git is not already installed you can probably
most easily use the standard package management systems of your OS to
install git.  For Windows, or to install it by hand on Linux/Mac, you
should get the package from the SCM git site:

- [Git download package](https://git-scm.com/downloads)

### Clone Class Repository

The class repository for our Introduction to Computational Science class
can be found at: https://github.com/csci560-nndl/nndl

To clone the repository from a dos terminal or command line prompt, once
git is installed, do the following

    $ git clone https://github.com/csci560-nndl/nndl


### Test Python, Jupyter and Class Notebooks

There are multiple ways to start up a Jupyter notebook server on your
system once you have Python and Jupyer installed.  From a dos prompt
or the command line, first change to the directory where you cloned
your class repository into, and then execute the command

    $ jupyter notebook

This will start up a notebook server, and on most systems will open
up a file browser inside of your default web browser, in order for
you to browse and select iPython notebooks for execution.

