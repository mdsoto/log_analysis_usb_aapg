<img src="portada.png" style="width:1000px" align="center">

<h2>About this material</h2>

This was the core material of the online course Basic Python for Log Analysis, given at the Universidad Simon Bolivar (USB) AAPG Student Chapter (Caracas, Venezuela), in January 2021. It was created and given by Manuel David Soto (MSc in Geology, University of Texas at Austin, USA), with organization of Ulises Berman (Student of Geophysical Eng, USB), President of the USB AAPG student chapter. In the course participated 25 students and professionals from six countries; Argentina, Bolivia, Colombia, Peru, USA, and Venezuela, the organizer country.

<h2>Objectives</h2>

Log analysis (LA) or petrophysics is the geosciences discipline that integrate and interpret all the data acquired in the initial live of the wells. Python (programing language) and its different libraries (both free) provide extraordinary and scalable tools for log analysis and other geosciences disciplines. The course covers basic tools (loading and writing information, plotting, basic statistics, execution of function and formulas, summaries, regressions, …) of this general-porpoise programming language with direct application in LA. The participants have to do reinforcement homework exercises after every session.

<h2>Course format</h2>

The course is composed by an introduction (pdf not provided here) and 3 online sessions of 2 hours and 45 minutes (15 minutes break). Before session 1, the participants have to read the introduction and installed Python and Jupyter Notebook according to the instructions given in the introduction. Installation problems cannot be tackled during the sessions. Each session has a folder with its corresponding data, images, and Jupyter Notebooks (theory and exercises). Along the course, Jupyter Notebook is the environment that we use to develop our Python codes. The exercises are shown in all theoretical Notebooks (Session_1_variables_data_arrays_functions.ipynb) however, it is recommended to work the exercises in the Notebook intended just for that (Session_1_exercises.ipynb), in that way the theoretical Notebook is preserved for future references.



<h2>Attendees and requirements</h2>

Geoscientist and engineers with basic knowledge of open-hole log analysis. Personal computer (with Windows 10 preferably) with Internet connection.

<h2>Summarized table of contents</h2>

* Introduction (pdf not provided here): Coding. Python and its packages. Installing Python & Jupyter
* Session 1: Variables and  data types. Arrays. Python structure and functions
* Session 2: Flow control. Read and write text files. Plots. Basic statistics
* Session 3: Well information loading and verification. Parameters selection. Output logs and summation. Simple estimation of rock typing and K

<h2>Libraries for each session</h2>

Here is a list of commands that need to be executed in a Command Prompt window (CMD) in order to have the necessary libraries for each session:

* Session 1:

        python -m pip install --upgrade pip
        pip install jupyter 
        pip install numpy
        pip install matplotlib

* Session 2:

        pip install xlrd
        pip install pandas
        pip install scipy
        pip install seaborn
        
* Session 3:

        pip install autopep8
        pip install jupyter_contrib_nbextensions
        pip install jupyter_nbextensions_configurator
        jupyter contrib nbextension install --user
        jupyter nbextensions_configurator enable --user
        pip install pyqt5	
        pip install pillow
        pip install -U scikit-learn
        
<h2>Note on the Readme files</h2>

The Readme(.md) files were obtained from the Jupyter Notebooks (.ipynb) thanks to the following wonderful converter:

https://alldocs.app/convert-jupyter-notebook-to-markdown
    
As no conversion is perfect, the Readme files inside the sessions are just a visual reference, the real performance of the cell is obtained only by running the corresponding Jupyter Notebooks.
