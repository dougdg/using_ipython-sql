# Integrating IBM Db2 with Jupyter Notebooks in Watson Studio using the ipython-sql package.

## Introduction
This repository contains a jupyter notebook (two versions that differ only in language) that demonstrate how to use the ipython-sql package with IBM Db2 cloud service. 
The jupyter notebook is suposed to be executed in Watson Studio (the IBM data science ecossystem), but with little adaptations it can be executed locally, using only the IBM Db2 service in the Cloud.

## Required IBM Cloud Services

<a href="https://console.bluemix.net/catalog/services/watson-studio">
    <img src="https://i.imgur.com/PUUM0g8.png" alt="Watson Studio">
</a> 

<a href="https://console.bluemix.net/catalog/services/db2">
    <img src="https://i.imgur.com/WoS3hOu.png" alt="Watson Studio">
</a>

## Setup

1. After creating an IBM Db2 service instance, unzip and upload the three .csv files (choose automatic schema detection);
2. Copy the IBM Db2 service credentials for future use (connection through ipython-sql package);
3. After creating an IBM Watson Studio service instance, create a new data science project;
4. Inside the project screen, go to assets tab and create a new Jupyter Notebook (copy and paste the .ipynb file from this repository at the "import from URL field", and also choose one of the python runtimes);
5. Now you are ready to execute the jupyter notebook and make queries using the %sql magic.
