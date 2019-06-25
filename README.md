# Data & AI Workshop - Data Understanding and Processing

## Objective

This workshop will walk you through some of the fundamental early stages of the Data Science / ML workflow. We will be exploring different aspects of data understanding, visualization and processing. By the end of these labs/tutorials, you should understand:

- The use of Jupyter Notebooks in IBM Watson Studio
- How to load data sets with open source libraries
- How to visualize data sets through code and no-code options
- How to process data sets

### Tools Used

- Watson Studio [(docs)](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/welcome-main.html?audience=wdp)
- Apache Spark Environments [(docs)](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/environments-parent.html?audience=wdp)
- [Jupyter Notebooks](http://jupyter.org/)
- Several Python Libraries: Pandas, Seaborn, Matplotlib, [PixieDust](https://github.com/pixiedust/pixiedust)

## Requirements

- [IBM Cloud Account](https://cloud.ibm.com)

***

## Workshop Flow

Most of these labs are written in python and using Jupyter Notebooks. One of the most common python libraries used for data analysis and manipulation is [pandas](https://pandas.pydata.org/), which is used throughout the labs. For a quick tutorial around pandas, feel free to run through the material found here - [IBMDeveloperUK pandas-workshop](https://github.com/IBMDeveloperUK/pandas-workshop).

### Prerequisites

1. Store this repository on your local computer.

   If you have GIT on your machine, clone this repository locally. Open a terminal and run:

   ```
   $ git clone https://github.com/jrtorres/dsai-workshop-dataprocessing.git
   ```

   If you do NOT have GIT on your machine, you can just download the repository as a ZIP file. In the browser window, select :

    ![Download Repo](docs/images/ss0.png)

1. Ensure you have access to a Waston Studio Instance. If you need to provision an instance, see the instructions in the [Setup Watson Studio doc](EnvironmentSetup.md)

### (Optional) Lab 0 - Pandas For Visualization

In this optional lab, we will be using pandas & geopandas to explore and visualize data. The goal of this lab is to get you familiar with pandas, loading data, understanding whats in the data and some aspects of visualization.

Follow the instructions in this [README](https://github.com/jrtorres/geopandas-workshop)

### Lab 1 - Pandas and Pixie Dust

In this lab, we will start to explore using helper libraries in our analysis tasks. In this example, we will use Pixie Dust to simplify the visualization aspects of our data analysis.

Follow the instructions in the [Diet & Disease Exploration Readme](Diet-Disease-Exploration.md)

### Lab 2 - Data Refinery for Visualization

In this lab, we will take a quick break from coding and explore the options for data visualization with no development requirements. In this case, we will use the Data Refinery tool of Watson Studio to help us visualize aspects of a data set.

Follow the instructions in the [Data Refinery Readme](datarefinery/README.md)

### Lab 3 - Data Understanding Example Insights

Finally, with a bit of background in both a code based and zero code based approach to data exploration, we will turn to an example of applying these data processing/visualization techniques to a scenario where we are trying to understand why employees might leave a company (Employee Attrition Problem). 

Follow the instructions in the [Employee Attrition Readme](Employee-Attrition-Exploration.md)

## Related Links

There is lots of great information, tutorials, articles, etc on the [IBM Developer site](https://developer.ibm.com) as well as broader web. Here are a subset of good examples related to data understanding, visualization and processing:

- [Explore Car Accidents Reports](https://dataplatform.cloud.ibm.com/exchange/public/entry/view/5a7051906b8fe9cc1ba126b53edd948e)
- [Visualizing Flood Data with Pandas, Matplotlib, and PixieDust](https://github.com/IBM/visualize-data-with-python)
- [Visualize Food & Disease Related Data](https://developer.ibm.com/patterns/create-visualizations-to-understand-food-insecurity/)
- [Analyze Shopping Data](https://developer.ibm.com/patterns/analyze-historical-shopping-data-spark-pixiedust-jupyter-notebook/)
- [PCA](https://developer.ibm.com/patterns/deep-dive-into-pca-principal-component-analysis/)
- [Data Prep using Data Refinery](https://developer.ibm.com/tutorials/data-preparation-with-ibm-data-refinery/)

## General Links

- [IBM Developer](https://developer.ibm.com)
- [Watson Studio](https://dataplatform.ibm.com/)
- [Watson Studio Overview](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/overview-ws.html?audience=wdp&context=wdp&linkInPage=true)
- [Watson Machine Learning Python SDK](https://wml-api-pyclient.mybluemix.net/)
- [Watson Studio Video Learning Center](https://www.youtube.com/playlist?list=PLzpeuWUENMK3u3j_hffhNZX3-Jkht3N6V)
- [Data Science Code Patterns](https://developer.ibm.com/code/technologies/data-science/)
