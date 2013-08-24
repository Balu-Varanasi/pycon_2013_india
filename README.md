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
- **9:30 - 11:00**: Part 1
   + Getting started
   + Representation and Visualization of Data
   + Basics of Machine Learning and the scikit-learn syntax
   + Supervised learning
       * _regression_
       * _classification_
   + Unsupervised learning
       * _clustering_
       * _dimensionality reduction_

- **11:00 - 11:10**: short break

- **11:10 - 12:00**: part 2
   + Validation and testing of models
   + examples
