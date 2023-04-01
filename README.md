# Rise and Fall of Programming Languages
## Description
How can you tell what programming languages and technologies are used by the most people? How about what languages are growing and which are shrinking, so that you can tell which are most worth investing time in? One excellent source of data is [Stack Overflow](https://stackoverflow.com/), a programming question and answer site with more than 16 million questions on programming topics. By measuring the number of questions about each technology, you can get an approximate sense of how many people are using it. In this project, you'll use open data from the [Stack Exchange Data Explorer](https://data.stackexchange.com/) to examine the relative popularity of languages like R, Python, Java and Javascript have changed over time.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with R kernel support. Make sure to install the required packages such as `tidyverse`. You can do this by running the following commands in a code cell within the notebook:
``` r
install.packages("tidyverse")
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the R kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Install the R kernel for Jupyter Notebook by running the following commands in your R console:
``` r 
install.packages("IRkernel")
IRkernel::installspec()
```
After completing the installation, launch Jupyter Notebook, navigate to the folder containing the notebook file, and open it to begin running the analyses.
## Contents
1. **Data on tags over time:** An overview of the dataset containing information about tags and their usage over time.
2. **Now in fraction format:** Transforming the data to represent tag usage as a fraction of total questions asked per year.
3. **Has R been growing or shrinking?:** Analyzing the trend of R programming language usage on Stack Overflow.
4. **Visualizing change over time:** Creating visualizations to better understand the changes in tag usage over time.
5. **How about dplyr and ggplot2?:** Investigating the trends of dplyr and ggplot2 package usage within the R community.
6. **What are the most asked-about tags?:** Identifying the most popular tags on Stack Overflow.
7. **How have large programming languages changed over time?:** Analyzing the changes in the popularity of major programming languages over time. 
8. **Some more tags!:** Exploring additional tags and their usage trends on Stack Overflow.  