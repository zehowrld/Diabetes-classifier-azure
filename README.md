# Diabetes-classifier-azure

1. **Explored Azure Machine Learning workspace resources and assets:**
   - Utilized developer tools for workspace interaction to familiarize myself with the environment.
   - Made data available in Azure Machine Learning, enabling seamless access and integration of data into my machine learning projects.
   - Worked with compute targets in Azure Machine Learning, understanding how to allocate computational resources efficiently.
   - Configured environments in Azure Machine Learning to ensure consistency and reproducibility in my experiments.

2. **Worked with data in Azure Machine Learning:**
   - Implemented techniques to make data available in Azure Machine Learning, facilitating data preprocessing and analysis.

3. **Experimented with Azure Machine Learning:**
   - Employed Automated Machine Learning to identify the best classification model, optimizing model selection and performance.
   - Tracked model training in Jupyter notebooks using MLflow, enhancing experiment reproducibility and collaboration.

4. **Trained models with scripts in Azure Machine Learning:**
   - Ran training scripts as command jobs in Azure Machine Learning, automating model training processes.
   - Tracked model training progress and performance with MLflow in jobs, enabling comprehensive monitoring and evaluation.
   - Conducted hyperparameter tuning with Azure Machine Learning, optimizing model parameters for improved performance.

5. **Optimized model training with Azure Machine Learning:**
   - Utilized Azure Machine Learning to run training scripts as command jobs, enhancing efficiency and scalability.
   - Tracked model training progress and performance using MLflow in jobs, ensuring visibility and transparency throughout the training process.
   - Conducted hyperparameter tuning with Azure Machine Learning, fine-tuning model parameters for optimal results.
   - Ran pipelines in Azure Machine Learning, streamlining and automating the end-to-end machine learning workflow.

6. **Deployed and consumed models with Azure Machine Learning:**
   - Deployed models to managed online endpoints, making them accessible for real-time inference.
   - Deployed models to batch endpoints, enabling efficient and scalable batch processing.

## RAI(responsible AI) Dashboard 
![Dashboard dia](https://github.com/user-attachments/assets/c3fcf7f9-ab9c-402c-92b9-033d49d77203)
![dashboard 1 dia](https://github.com/user-attachments/assets/372baa33-21a3-4dd5-b6fa-ab45c4d8604a)

## Setup Instructions

### Step 1: Create the Workspace and Compute Resources

1. **Open Azure Portal:**
   - In your browser, navigate to the [Azure portal](https://portal.azure.com/).
   - Sign in with your Microsoft account.

2. **Open Cloud Shell:**
   - Select the [>_] (Cloud Shell) button at the top of the page, to the right of the search box.
   - Choose **Bash** if prompted. The first time you open the Cloud Shell, you will be asked to choose between Bash and PowerShell.
   - Ensure the correct subscription is specified and select **Create storage** if prompted to create storage for your Cloud Shell. Wait for the storage to be created.

3. **Clone the Repository:**
   - In the terminal, enter the following commands to clone this repository:

     ```bash
     rm -r azure-ml-labs -f
     git clone https://github.com/zehowrld/Diabetes-classifier-azure.git azure-ml-labs
     ```

4. **Navigate to the Setup Script:**
   - After the repository has been cloned, enter the following commands to change to the folder for this lab and run the `setup.sh` script:

     ```bash
     cd azure-ml-labs/Labs/(Please Enter the Lab Number Here)
     ./setup.sh
     ```

   - Ignore any error messages that say that the extensions were not installed.
   - Wait for the script to complete (this typically takes around 5-10 minutes).

### Step 2: Clone the Lab Materials

1. **Open Azure Machine Learning Studio:**
   - In the Azure portal, navigate to the Azure Machine Learning workspace named `mlw-dp100-...`.
   - Select the Azure Machine Learning workspace, and on its Overview page, select **Launch studio**. A new tab will open in your browser with the Azure Machine Learning studio.
   - Close any pop-ups that appear in the studio.

2. **Verify Compute Resources:**
   - Within the Azure Machine Learning studio, navigate to the **Compute** page and verify that the compute instance and cluster you created exist. The compute instance should be running, and the cluster should be idle with 0 nodes running.

3. **Install Python SDK:**
   - In the **Compute instances** tab, find your compute instance, and select the **Terminal** application.
   - In the terminal, install the Python SDK on the compute instance by running the following commands:

     ```bash
     pip uninstall azure-ai-ml
     pip install azure-ai-ml
     ```

   - Ignore any error messages that say the packages couldn’t be found and uninstalled.

4. **Clone the Git Repository:**
   - Run the following command to clone a Git repository containing a notebook, data, and other files to your workspace:

     ```bash
     git clone https://github.com/zehowrld/Diabetes-classifier-azure.git azure-ml-labs
     ```

## Reflection

This project provided me with valuable hands-on experience in utilizing Azure Machine Learning to develop, train, and deploy machine learning models.I gained a comprehensive understanding of Azure's capabilities for data science and machine learning tasks, empowering me to tackle real-world challenges with confidence.
