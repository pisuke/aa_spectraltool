# aa_spectraltool

This is a [Python](https://www.python.org/) [Jupyter notebook](http://jupyter.org/) that uses the [Colour library](http://colour-science.org/) to analyse light spectra captured with a [paper spectrometer](https://publiclab.org/sites/default/files/8.5x11mini-spec3.8.pdf).

## Prerequisites

The aa_spectraltool Jupyter notebook uses several scientific Python libraries:

* Libraries included in the [Anaconda Python Distribution](https://www.continuum.io/downloads)
 * [numpy](http://www.numpy.org/)
 * [scipy](https://www.scipy.org/)
 * [matplotlib](http://matplotlib.org/)
 * [sklearn](http://scikit-learn.org/)
 * [PIL](http://www.pythonware.com/products/pil/)
 * [itertools](https://docs.python.org/3/library/itertools.html)
 * [csv](https://docs.python.org/3/library/csv.html)

* [Colour](http://colour-science.org/)

These libraries must be installed before the next step. The easiest way to install them is to download and install Anaconda and then to download and install Colour.

### Download and installation of Anaconda

1. Follow this link [https://www.continuum.io/downloads](https://www.continuum.io/downloads) to download the Anaconda distribution for your operating system. Download the Python 3.5 version.

2. Once the installation package has been downloaded, execute it and follow the instructions.

3. Anaconda is now ready to be used. A simple way to use it is to launch the Jupyter Notebook from the Anaconda Navigator application. In a Windows system, go to the Anaconda application menu and launch it. On a Mac OS X system, find the Anaconda Navigator app in your user anaconda folder, or just use the cmd+space keyboard combination and type "navigator".

![Anaconda Navigator](https://docs.continuum.io/_images/navigator-home-1-3.png)

4. Click the Launch button in the Jupyter Notebook application tile shown inside Anaconda Navigator. A browser window similar to the one shown below should appear.

![Jupyter Notebook](https://lh4.googleusercontent.com/gm2oSwAoX6I5mO2m8rq1MyPI47Re7bMpC4KxofZOk5Crl7pIKhLPa9W7tdAzLKdG-urpze1Nupwx3pA=w2346-h1606-rw)

### Download and installation of Colour

1. Open a terminal window
 * On Windows, click on the start icon and type cmd
 * On MacOS X, launch the Terminal application
 
2. Ensure that your Internet connection is working and Type the following command in the terminal window:
```
pip install colour-science
```
3. Optionally, to check that colour has been installed, type the following in the command line. you should see something similar.
```
python
Python 3.5.1 |Anaconda custom (x86_64)| (default, Dec  7 2015, 11:24:55)
[GCC 4.2.1 (Apple Inc. build 5577)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import colour
>>> dir(colour)[0]
'ACES_2065_1_COLOURSPACE'
```

## Download and installation of the aa_spectraltool

1. Download the aa_spectraltool from this link: [https://github.com/pisuke/aa_spectraltool/archive/master.zip](https://github.com/pisuke/aa_spectraltool/archive/master.zip)

2. Unzip the file in your preferred location. 

3. Open a terminal window
 * On Windows, click on the start icon and type cmd
 * On MacOS X, launch the Terminal application
 
4. Change directory in the terminal window to the folder where you have unzipped the aa_spectraltool files. 
 * On both Windows and MacOSX this can be accomplished by typing:
  ```
  cd 
  ```
 into the terminal window and dragging the folder icon to the terminal so that it shows up next to the "cd " command with a space in between.
 * Press the Enter key to change directory and then execute the "jupyter-notebook" command
  ```
  jupyter-notebook
  ```
  This command will open a browser window similar to the one show below.
  
  ![aa_spectraltool](https://lh6.googleusercontent.com/c3UnmYNgtG50oKfbjHE-cPUeNCceIIpSWSZ3Gdt18GNc3HVmZGQFOBqI1ihlQTZPXdfdyTkWLn9YLlw=w2346-h1606-rw)


## Use


