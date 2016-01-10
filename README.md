
The python notebooks in this repo are for the workshops I held on machine learning during Fall Quarter 2016 at  UCLA for ACM'S AI club. It is an introduction to machine learning with scikit-learn and python. Currently, workshop one is up, which was help on October 12, 2015. 

In order to run the ipython notebook, just follow the steps below

    git clone https://github.com/abcde13/MachineLearningWrkshp.git
    cd MachineLearningWrkshp.git
    ipython notebook

If ipython doesn't work, first see if you have python installed by doing `python --version`. If you see `command not found: python` then you need to install it.

Follow this link to install it: http://ipython.org/install.html. However, if you have pip installed (check via the same process as above),
I recommend doing 
    
    pip install ipython[notebook] ipython[qtconsole]

after running `pip intall ipython`.

If you don't have anything installed, or you want to use Anaconda because you like the way it sounds, then follow the instructions in the link above
to download it. Then, run 

    conda update conda

    conda update ipython ipython-notebook ipython-qtconsole


This should give you all the necessary tools to start using the notebook.

If you truly want to used the notebook the way I gave the presenation, try running this:

    ipython nbconvert --to slides --post serve title-of-the-notebook.ipynb

where <i>title-of-the-notebook</i> is one of the ipython notebooks above, such as `Intro\ to\ Machine\ Learning` or `Unsupervised\ Learning`

This uses nbconvert to turn the notebook into a presenation via Reveal.js, and a server is then spun up to view the presentation. 
 
Once you've got the presentation up, you can code the examples used by running `ipython qtconsole`. The qtconsole is necessary because provides a GUI with which to plot things on.

Clicking on th .ipynb file also renders it fully, if you just want to view the entire presenation passively.
