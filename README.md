# Paris Olympic Data Analysis End-To-End Data Engineering
## Introduction
This project extracts data from **Kaggle API** using *Azure Data Factory* to load raw data onto the **Azure Data Lake** storage. Then using **Databricks** to write spark code, transform it to data for analysis and load it back to **Azure Data Lake**, again. Once that is done, we will use **Azure Synapse analystics** to run the SQL queries on top of the transformed data so that we can find the the insights and get visualization.
## Architecture
![Architecture](https://github.com/nvkhoa14/Paris-Olympic-Data-Engineer/blob/main/src/pipeline.png)
## DEMO
### Get data from Kaggle and load into Data Lake.
Example data [here](https://github.com/nvkhoa14/Paris-Olympic-Data-Engineer/tree/main/dataset).
![Factory](https://github.com/nvkhoa14/Paris-Olympic-Data-Engineer/blob/main/src/factory.png)
Loaded Data.
![Lake](https://github.com/nvkhoa14/Paris-Olympic-Data-Engineer/blob/main/src/factory.png)
### Transform data using Databricks.
Transformed data and new schema created and loaded in [notebook](https://github.com/nvkhoa14/Paris-Olympic-Data-Engineer/blob/main/Paris%20Olympic%20Tranformation.ipynb).
### Tables.
![Synapse](https://github.com/nvkhoa14/Paris-Olympic-Data-Engineer/blob/main/src/synapse.png)
### Analize and visualize.
***...On processing :(***
