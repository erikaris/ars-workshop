Archive Research Services Workshop - Notebooks Edition
======================================================

## Initial Setup

Please make sure that you've run through steps 3-7 of the [Initial Setup](https://github.com/vinaygoel/ars-workshop#initial-setup)

#### Install Anaconda

Follow these [instructions for installing Anaconda](http://docs.continuum.io/anaconda/install).
Make sure that location of the Anaconda installation directory has been added to the bash PATH.

You can test that Conda has been installed by running:
```
conda --version
```

#### Create the notebook environment
```
./notebooks/create-environment.sh
```

## IPython Notebooks

You're now ready to start working with [IPython notebooks](https://ipython.org/ipython-doc/3/notebook/notebook.html) and will only need to run the following commands in the future.

To start, run
```
source activate notebooks
ipython notebook
```
This will open up the [IPython Notebook Dashboard](http://localhost:8888/) on your configured web browser. In the dashboard, navigate to the `notebooks/` folder and open your notebook of choice.

Once you're done with the notebooks, run
```
source deactivate
```
