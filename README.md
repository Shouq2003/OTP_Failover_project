This project is an AI-based solution designed to predict OTP (One-Time Password) delivery failures and determine when to switch to a backup vendor to ensure reliability. Companies relying on OTP systems often face issues when their primary SMS gateway fails, leading to delays, customer dissatisfaction, and security risks. This model addresses the problem by analyzing key factors such as response time, error rate, primary vendor failure rate, backup vendor success rate, retry attempts, and time period (Peak/Off-Peak). 

It is built using Pythonfaker to creat fake data , with LightGBM for high-performance modeling, Scikit-learn for training and evaluation, and Pandas & NumPy for data processing. The model achieves 99% accuracy, with a False Positive Rate of 1.86% and a False Negative Rate of 0.97%, ensuring robust and reliable predictions. 

The repository includes the OTP_Failover_Dataset.csv (dataset), otp_failover_best_model.pkl (trained model), and OTP Failover -Masar By Sani.ipynb (notebook with full implementation) and Demo for the model to run the demo in google colab please be sure about load the model the the path for it. To run the project, install dependencies with pip install -r requirements.txt, then launch the interactive demo using Gradio. 

The project can be further enhanced with real-time monitoring and integration into enterprise authentication systems.
