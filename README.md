
The python notebook in this repo is for a talk I gave about machine learning on 30 April, 2015 at UCLA for ACM'S AI club. It was an introduction to machine learning with scikit-learn. 

In order to run the ipython notebook, just follow the steps below

    git clone https://github.com/abcde13/MachineLearningWrkshp.git
    cd MachineLearningWrkshp.git
    ipython notebook

There are 2 versions of the notebook, v3, and v4 (v4 has no version on it), which correspond with how nbconvert is creating the notebook.
Run whichever one currently works in your environment, they should be almost identical. The only reason I have two different versions
is due issues manifesting when converting the notebook to a presenation via the --to slides --post serve arguments for nbconvert.

If you truly want to used the notebook the way I was going to give the presenation, try running this:

    ipython nbconvert MachineLearningWrkshp.ipynb --to slides --post serve

This uses nbconvert to turn the notebook into a presenation via Reveal.js, and a server is then spun up to view the presentation. You may
have to deal with missing packages or versioning issues to get this to work, but when you do, you'll see how cool it is!

And for the extremely lazy, the simple HTML file is also in the repo, which can itself be viewed for the tutorial.
