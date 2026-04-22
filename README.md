# Lab: Setting Up and Using a Cloud-Based Jupyter Environment

This repository contains a hands-on lab designed for **Week 7 of the Data Science Course**. The primary objective is to familiarize students with cloud-based computing using **Google Colab**, a powerful tool for developing and sharing machine learning projects without requiring local installation.

## Objectives
By completing this lab, you will learn how to:
1. Launch and navigate a Jupyter Notebook in the cloud via Google Colab.
2. Optimize performance by switching to a **free GPU** (T4) runtime.
3. Persist data and models by **mounting Google Drive**.
4. Manage environments by installing specific Python libraries in a cloud instance.
5. Train a real-world Machine Learning model using cloud resources.
6. Save and export trained models for future use.

##  Setup Instructions
To get started with this lab:
1. **Open the Notebook**: Upload `Lab_Cloud_Jupyter_Setup.ipynb` to [Google Colab](https://colab.research.google.com).
2. **Sign In**: Ensure you are signed into your Google account.
3. **Save a Copy**: Go to `File` → `Save a copy in Drive` to enable editing and saving your progress.
4. **Hardware Acceleration**: 
   - Go to `Runtime` → `Change runtime type`.
   - Select **T4 GPU** (or available GPU) under Hardware accelerator.
   - Click **Save**.

##  Lab Workflow
The lab is structured into five key steps:
- **Step 1: System Audit**: Checking the specifications of the virtual machine provided by Google.
- **Step 2: GPU Activation**: Verifying the presence and status of the GPU.
- **Step 3: Drive Integration**: Connecting your Google Drive to the notebook for persistent storage.
- **Step 4: Library Management**: Using `pip` to install specialized libraries (e.g., `joblib`, `tensorflow`).
- **Step 5: ML Workflow**: Training a classification model, evaluating it, and saving the model file (`.pkl`) directly to your Drive.

##  Exercises Included
The lab includes a **Challenge Section** where students must:
- Extract and visualize feature importance from a trained model.
- Verify TensorFlow GPU compatibility.
- Implement data visualization using `matplotlib` or `seaborn`.

##  Submission
Follow the instructions within the notebook for final naming conventions:
- **Filename Format**: `Lab32_Cloud_YourName_RollNumber.ipynb`
- Ensure all outputs are visible before sharing the link or downloading the file.

---
*Developed for Data Science — Week 7: Cloud Computing for Data Science.*
