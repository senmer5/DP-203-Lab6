# DP-203-Lab6
Spark Data Transformation with Synapse Studio ✨

Overview 📝

This guide walks you through transforming data using Apache Spark in Azure Synapse Studio. By the end of this guide, you will have learned how to use the provided notebook Spark Transform.ipynb to perform the ETL (Extract, Transform, Load) process on your data.

Prerequisites 🛠️

Before you start, make sure you have the following:
	•	Azure Synapse Workspace: Set up a Synapse workspace in your Azure portal.
	•	Storage Account for Data Pond: A storage account configured to store your raw data.
	•	Apache Spark Pool: A Spark pool to handle your data processing.

Steps 🔍

1. Open Azure Synapse Studio 🌐
	•	Sign in to the Azure portal and navigate to your dp203-xxxxxxx resource group.
	•	Select your Synapse workspace.
	•	On the Overview page, click on Open Synapse Studio. This will open Synapse Studio in a new browser tab.
	•	If prompted, sign in using your Azure account credentials.

2. Download the Spark Transform.ipynb File 📥
	•	Download the Spark Transform.ipynb file from the following path:
Allfiles/labs/06/notebooks
	•	This file contains the necessary code to transform the data, often provided as a sample process for students or data engineers.

3. Import the Notebook into Synapse Studio 📂
	•	In Synapse Studio, go to the Develop page.
	•	Expand the Notebooks tab.
	•	Click the + icon in the top right corner and select Import.
	•	In the dialog that appears, browse and select the Spark Transform.ipynb file you just downloaded.

4. Connect the Notebook to the Spark Pool 🔗
	•	Open the imported notebook.
	•	To execute the notebook, connect it to a Spark pool. From the dropdown, select the Sparkxxxxxxx pool. This pool will provide the necessary computational power for transforming your data.

5. Run the Cells in the Notebook ▶️
	•	Go through the notebook and run each code cell sequentially. Each cell performs specific operations to transform your data.
	•	Extract: Fetch the data 📊
	•	Transform: Process the data (e.g., cleaning, filtering, grouping) 🧹
	•	Load: Output the transformed data to a target source (e.g., a database or data lake) 💾

General ETL Process 🔄
	1.	Extract: The first step involves extracting data from your source system.
	2.	Transform: The data is processed—this includes tasks like cleaning, filtering, and shaping the data into the desired structure.
	3.	Load: Finally, the transformed data is loaded into a target data source, such as a database or a data lake.

Conclusion 🎉

By following these steps, you’ll have successfully transformed your data using Spark in Synapse Studio. This process is vital for data engineers and data analysts working with large datasets in cloud environments, providing them with the tools to effectively handle and analyze data. 🚀

## Screenshots

<img width="982" alt="1" src="https://github.com/user-attachments/assets/b4aff107-82da-45b6-8424-6ee963f6ae91" />


<img width="979" alt="2" src="https://github.com/user-attachments/assets/64424e27-5361-41d3-9a30-780ccbb6eb3b" />


<img width="979" alt="3" src="https://github.com/user-attachments/assets/55c1ad1d-e01b-4d4a-9cf8-c77f7d7efba7" />


<img width="979" alt="4" src="https://github.com/user-attachments/assets/3dbf6b61-7a9d-49f1-ba88-639a664f353c" />


<img width="974" alt="5" src="https://github.com/user-attachments/assets/836b29de-0530-40a6-bc0c-1809c3445232" />


<img width="980" alt="6" src="https://github.com/user-attachments/assets/6c4af666-8552-4e5e-9986-57b73c312b81" />

