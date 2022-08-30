# ENVIRON/ENERGY 716 - Modeling for Energy Systems - LAB

In this course you will learn how to perform simple calculations, rearrange data sets and solve optimization models using Python.

We will use Python and Google Colaboratory to develop our codes. Google Colab is a tool that allows you to write, run and share Python codes within your browser without the need to install any software. Google Colab documents have extension *.ipynb* (like Jupyter notebooks) and use the Markdown format which means you can create a document that contains text, images and executable code.

We will use this GitHub folder to share the *.ipynb* scripts developed in the labs as well as some additional resources. GitHub is a cloud-based hosting service for software development where users can collaborate and store their codes.

If you have any questions, please use the email distribution list *ask716@duke.edu* to ask. <br>

## Course Set Up

As mentioned before we will use Google Colab to run our Python code we are calling it option 1. But there are two other options to run Python scripts as stated below.

* **Option 1 (preferred):** Using Google Colaboratory on Duke machines or personal laptop. That's teh option we will use in the labs. *No software installation required.* <br>
* **Option 2:** Using Duke Jupyter Notebook Container on Duke machines or personal laptop. *No software installation required.*  <br>
* **Option 3:** Using Jupyter notebook and Anaconda on your personal computer, i.e., running the scripts locally in your computer. *Software installation required.* <br>

Note that with Option 1 you can keep running Python scripts on your personal computer after you graduate, while the Jupyter containers will only be available to you while you are at Duke.

## Option 1: Getting Started With Google Colab and Python

Google Colaboratory, or “Colab” for short, is a web-based iPython Notebook service for interactive coding. It allows you to write and execute Python in your browser, with zero configuration required, free access to GPUs and easy sharing. Zero configuration required means you do not need to have Python, Anaconda and libraries installed to your local machine. Google Colab is very similar to Jupyter Notebook.

To set up your Google Colab go to your Google Drive and select New.

![Screenshot](/_Images/Picture1.png)

Navigate to More > Connect more apps.

A pop-up window will appear. Scroll down until you find Colaboratory.


Select Colaboratory and on the next pop-up window click Install.


You are all set!

You can also mount Colab to your Google Drive by simply opening a colab window (e.g. https://colab.research.google.com/notebooks/intro.ipynb), locating the MountGoogleColab.ipynb available on our GitHub repository (https://github.com/lmmlima/ENV716_EnergyModeling_F2021) and running it.

The easiest way to save Colab notebooks is to save it in your Google Drive. Click File > Save a copy in Drive. Once you saved a copy, you can open it from your Google Drive or Colab dashboard.
Please create a folder for this course (e.g. ENV716) in your Google Drive and save all Colab notebook files in there for easy access.

Bash commands can be run in your notebook (similar to how you would do in your terminal) by prefixing the command with ''!''. For example, '!pwd' command prints out the pathway to the current working directory. '!ls' command prints out a list of contents in current directory.

Bash command can be used to install libraries. Most common libraries are already installed on Colab. If you need to install additional libraries you can use ‘!pip’

!pip install [library name]

To install other libraries available through Advanced Package Tool (apt) use ‘!apt-get’

!apt-get install [package name]

For more info visit
https://colab.research.google.com/drive/1YKHHLSlG-B9Ez2-zf-YFxXTVgfC_Aqtt#scrollTo=UTRJlO55LdKf


Your first code in Colab:

Now to check if everything is working, you can write a command to display a simple sentence “Hello World”. Open a new notebook on Colab and type the following command.

print('Hello World')


This will output the following:



If you get the same output above, then you’ve finished your first, and probably the simplest program using Python! Feel free to play with it and write anything else you want!



Once you open your first Colab file and mount to your google drive, a folder called "Colab Notebooks" will be created on you Google Drive. All files you create, edit and save a copy will be stored in that folder.

## Option 2: Jupyter Containers

An alternative to using Nicholas School machines or installing Anaconda and Python on a personal machine is to use one of Duke’s Jupyter containers. With this option there is no need to install any software. You can access your Jupyter session anywhere from any machine via a web browser.

You will you need to create/set up your Jupyter container.

* Step 1: Navigate to "https://cmgr.oit.duke.edu/containers" and log in with your net ID.
* Step 2: Click on the reserve Jupyter button (right column).

You now have a dedicated Jupyter machine and teh name Jupyter should appear in the left column. At the end of the semester Duke IT will send a message asking whether you want to extend your reservation.

When you need to resume work, simply return to the "https://cmgr.oit.duke.edu/containers" site and log in. You’ll see a button to access your existing container.

## Option 3: Getting Started With Python on your personal computer

Please follow the instructions on the Python 101 file and make sure everything is running on your computer.
There are two Python 101 files, one for Mac users and one for PC users.

Once Python is up and running and you got your "Hello World" message, you are ready to run your first .ipynb script.

* Step 1: Locate the file in the Github repo, for example <i> Lab1_SimpleCalculation.ipynb </i>. <br>
* Step 2: Right-click on <i> Raw > Download Linked File As </i>. Save it on a local folder in your machine. <br>
* Step 3: Open Jupyter notebook using your terminal (for Mac users) or Anaconda (for PC users). <br>
* Step 4: From the list of folders that appear on Jupyter web application, find the folder were you saved the <i> .ipynb </i> file. <br>
* Step 5: After you locate the file, click on it to open. Remember that to run it locally you need to perform the installation steps from Python 101 files. <br>
