# How to install the environement needed for the tutorial:

## Tools used in the tutorial:
* `NumPy`,`SciPy`: package for scientific computing with Python
* `iPython`: an interactive shell, we'll be working inside of a web interface called Jupyter (or IPython) Notebooks
* `Matplotlib`: usefull ploting library

## Installation of the environement 

### *Option 1:* using Anaconda (tested on Linux and MacOS)
1. Download and install on your computer Anaconda from [this site](https://www.continuum.io/downloads): all the needed librairies will be included (install the version with Python 3.5) 
2. Open an new shell: you should now be able to run the command `jupyter notebook` to launch the notebook
3. *Note:* In a Linux environment, if jupyter command is not available, make run that Anaconda is correctly loaded in your environement (in your ~/.bash_rc file, the following line should appear: `export PATH="/YourAnacondaInstallDirectory/bin:$PATH"`

### *Option 2:* run the evironement from the virtual box
1. Download and install the virtual box needed for your operating system: [VirtualBox](https://www.virtualbox.org/)
2. Download the environement OVA from [this link](http://w3.iihe.ac.be/~pvanlaer/Stats.ova) 
3. Import it in the virtual box (File>Import)
4. Start the virtual box (in case needed, the password is `stat`)
5. In a terminal, run the command `jupyter notebook` : the tree directory should appear in Firefox


## Testing the environement:
1. In a clean directory, download the [test notebook](http://w3.iihe.ac.be/~pvanlaer/InstallTest.ipynb)
2. Start the jupyter notebook (with the command `jupyter notebook`), you should see that in your web browser:
 ![screenshot](https://github.com/HuguesBrun/statTutorialBND/blob/master/image/jupyterImg.png)
3. Click on the notebook InstallTest.ipynb to open it
4. Check that the code in every single cell can be executed (go in the cell and then execute it by typing `Enter + Shift`)

## Notebooks for Saturday September 3rd practical:
1.They are on GitHub at the following links:
  * Short introduction to Python [here](https://github.com/HuguesBrun/statTutorialBND/blob/master/Short%20Introduction%20to%20Python%20.ipynb)
  * Begining of the statistical tutorial [here](https://github.com/HuguesBrun/statTutorialBND/blob/master/Statistical%20Analysis%20Tutorial.ipynb)
  * *Note:* All the GitHub package can be downloaded using this git command in a terminal `git clone https://github.com/HuguesBrun/statTutorialBND.git`
