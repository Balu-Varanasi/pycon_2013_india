PyCon India 2013 Scikit-learn Tutorial
================================

*Instructor: Bala Subrahmanyam Varanasi*

- email: <vabasu@gmail.com>
- twitter: [@vabasu](https://twitter.com/vabasu)
- github: [Balu-Varanasi](http://github.com/Balu-Varanasi)

This repository will contain files and other info associated with PyCon India
2013 scikit-learn tutorial.

Goals
-----
- **Introduce the basics of Machine Learning**, and some skills useful in practice.
- **Introduce the syntax of scikit-learn**, so that you can make use of the rich toolset available.

Installation Notes
------------------

This tutorial will require recent installations of *numpy*, *scipy*,
*matplotlib*, *scikit-learn* and *ipython* with ipython notebook.

The last one is important, you should be able to type:

    ipython notebook

in your terminal window and see the notebook panel load in your web browser.

For users who do not yet have these  packages installed, a relatively
painless way to install all the requirements is to use a package such as
[Anaconda CE](http://store.continuum.io/ "Anaconda CE"), which can be
downloaded and installed for free.

Downloading the Tutorial Materials
----------------------------------
I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

    git clone git@github.com:Balu-Varanasi/pycon_2013_india.git

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  I may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.

Data Downloads
--------------
The data for this tutorial is not included in the repository.  We will be
using several data sets during the tutorial: most are built-in to
scikit-learn, which
includes code which automatically downloads and caches these
data.  Because the wireless network
at conferences can often be spotty, it would be a good idea to download these
data sets before arriving at the conference.


Notebook Listing
----------------
These notebooks in this repository can be statically viewed using the
excellent [nbviewer](http://nbviewer.ipython.org) site.  They will not
be able to be modified within nbviewer.  To modify them, first download
the tutorial repository, change to the notebooks directory, and type
``ipython notebook``.  You should see the list in the ipython notebook
launch page in your web browser.


Detailed Outline Tutorial
-------------------------
- 0:00 - 0:15 -- Setup and Introduction
- 0:15 - 0:30 -- Quick review of data visualization with matplotlib and numpy
- 0:30 - 1:15 -- Representation of data in machine learning
  + Downloading data within scikit-learn
  + Categorical & Image data
  + Feature extraction
- 1:15 - 2:00 -- Basic principles of Machine Learning & the scikit-learn interface
  + Supervised Learning: Classification & Regression
  + Unsupervised Learning: Clustering & Dimensionality Reduction
  + Example of PCA for data visualization
  + Flow chart: how do I choose what to do with my data set?
  + Exercise: Interactive Demo on linearly separable data
  + Regularization: what it is and why it is necessary
    - Training set vs test set error
- 2:00 - 2:15 -- Break (possibly in the middle of the previous section)
- 2:15 - 3:00 -- Supervised Learning
  + Example of Classification: hand-written digits
  + Measuring prediction performance
  + Example of Regression: boston house prices
- 3:00 - 4:15 -- Applications
  + Examples from text mining
  + Examples from image processing

