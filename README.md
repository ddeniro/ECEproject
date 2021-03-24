# ECEproject

This project was programmed in Python, using *[Anaconda](https://www.anaconda.com/) toolkit for our necessary statistics, as well as plotting libraries. It is displayed using *[Jupyter](https://jupyter.org/)* Notebook, a great playground that made displaying this code more interactive.
The code blocks can be ran independently and the code can be edited and reverted by the viewer. 

## Installing dependencies

Interacting with the python in this notebook will require you use Jupyter yourself. The way I use this is through VSCode with these extensions: 
The extensions can be found through copying the ID next to their name and pressing CTRL+SHIFT+P and typing `install extensions` and selecting the first result. Paste the code `ms-toolsai.jupyter` for example, into the search bar in the left panel.

Anaconda is essentially an all-in-one solution for most data sciene code in Python. Which I have installed which allows me access to all of this libraries. They can all be installed individually however if you want to avoid installing 300 MB or so for an environment. `pip install seaborn` for example, will install seaborn and its dependencies (which just so happen to include numpy, scip,y matplotlib)
### VSCode extensions

* Jupyter : ms-toolsai.jupyter
* Python : ms-python.python

I simply launch the project.ipynb and can click the individual green run arrows next to each code block below, or we can run it all at once sequentially. Markdown is supported in their own blocks, and you can add your own python code blocks as well.


Note: Seaborn marks `distplot` as a deprecated, but their replacement `displot` was not included in my Anaconda installation.
