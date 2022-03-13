# Cryptocurrency Performance in Different Time Periods
---

##  Description:

This application will run clusters of cryptocurrency by their performance in different time periods (24 hours, 7 days, 14 days, 30 days, 60 days, 200 days, 1 year). After figuring the best k-value for the K-Means formula by using the Elbow Method, we will plot the clusters and the line chart of the Elbow Method.

--- 

## Installation:

We will need the following dependencies:
* **Fire**
  * [Fire](https://github.com/google/python-fire) - Used for the command line interface help page and entry point.
* **Questionary**
  * [Questionary](https://github.com/tmbo/questionary) - This is used as our interactive user prompts and dialogs.
* **hvPlot**
  * [hvPlot](https://github.com/holoviz/hvplot) - This will be used to plot the clusters and the line chart.
---

## How to Install:

To install the following packages we need to use terminal or git bash and type in the command line:

* **Fire**
    ```python
    pip install Fire
    ```
* **Questionary**
    ```python
    pip install questionary
    ```
* **HvPlot**
  
  It is preferable to create a different environment to use hvPlot. Installing hvPlot in a trusted [enviroment](https://hvplot.holoviz.org/developer_guide/index.html#id7) will make changes and adjustments for hvPlot to be used. (Click on the link for reference)
  ```python
  pip install hvplot
  ```

---


## Running the Application:
Upon running the application you will be shown Cryptocurrency coins with the price change percentage from 24 hours, 7 days, 14 days, 30 days, 60 days, 200 days, and 1 year. After inspecting the data we will plot a line graph of the changes. 

Then we will the best k value for the KMeans, by using the elbow curve formula. Later we will plot scatter chart with the price change of 24 hours and price change of 7 days.

After that we will find the optimized clusters with Principal Component Analysis (APC), after that we will decrease the amount of noise and find the best k value, then plot the scatter clusters the plots.

At the end will put the graphs and charts side by side to visualize them best.

---

## Contributors:
Brought to you by Angel Reyes.
---