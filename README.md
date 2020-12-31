# Programming for Data Analysis 2020 Project

This repository contains Brian Doheny's project submission for the Programming for Data Analysis 2020 module at Galway-Mayo Institute of Technology (GMIT).

This repository contains the following three files:
* README.md - this file you are currently reading.
* simulated-dataset.ipynb - A Jupyter Notebook showing my research for and simulation of a fictional Chinese language school in mainland China.
* world_populations.csv - A CSV file containing the populations for each country in the world, as provided by the [World Bank](https://data.worldbank.org/indicator/SP.POP.TOTL), with China, Hong Kong and Macau removed. This CSV is used for some of the calculations in simulated-dataset.ipynb 
* .gitignore

## How to use simulated-dataset.ipynb

In order to run the code snippets contained in this Jupyter Notebook on your local machine, you will first need to clone the repository. You can find the details on how to do this in [GitHub's documentation](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository) and I have outlined the steps below for convenience.

Step 1 - Click the "Code" button in the repository.

![here](https://screenshot.click/31_33-upgsx-93y7w.jpg)

Step 2 - Select "SSH" and click the clipboard icon next to the SSH address.

![here](https://screenshot.click/31_34-3z374-3v2lv.jpg)

Step 3 - Open Terminal, or whichever command line interface you use, and navigate to the directory you wish to clone this repository to.

Step 4 - Type "git clone" followed by the SSH addressed you copied earlier. You can do this by pasting it (CTRL+V or CMD+V).

Step 5 - Press enter.

## Package Versions used in simulated-dataset.ipynb

* Python - 3.8.5
* Numpy - 1.19.2
* Pandas - 1.1.3
* Matplotlib - 3.3.2
* Seaborn - 0.11.0

Throughout the simulated-dataset.ipynb, I use and refer to the syntax of Numpy v1.19. As this version of Numpy made significant changes to the pseudorandom number generation, it is important to ensure you have Numpy v1.19 at least.

You can find steps on how to update Python packages via Anaconda [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html#updating-packages).

