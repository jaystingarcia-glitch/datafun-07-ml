## Project 7: Machine Learning
Author: Jaystin Garcia
Date: February 2026

## Project Summary
In this module, you will create a guided project. There is no fixed specification — new topics, including introductory machine learning concepts, will be introduced as you progress. The project will use Jupyter for interactive exploration and analysis.
To begin, you will:
- Create a new project in GitHub for storing and sharing your work
- Clone the project to your local machine so you can use your development tools
- Set up a local virtual environment to manage dependencies
- Install the external packages needed for data analysis and machine learning

At minimum, the project environment should include:
- jupyterlab
- numpy
- pandas
- pyarrow
- matplotlib
- seaborn
- scipy
You may install additional packages as the project evolves.

## Project Setup (Windows / PowerShell, local computer C:)

1. **Clone the repository:**
  Open a terminal in your `Repos` folder and run:

  ```shell
  git clone https://github.com/jaystingarcia-glitch/datafun-07-ml.git
  cd datafun-07-ml
  code .
  ```

2. **Install recommended extensions:**
  When prompted, accept Extension Recommendations (click **Install All**).

3. **Set up the Python environment:**
  - Open a terminal in the root project folder.
  - If using `uv` (recommended):

    ```shell
    uv self update
    uv python pin 3.14
    uv sync --extra dev --extra docs --upgrade
    ```

## Code Updates
