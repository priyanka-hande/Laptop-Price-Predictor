# Laptop Price Predictor
This repository contains the code for a Laptop Price Predictor project, which aims to predict the price of a laptop based on various features such as brand, type, RAM, weight, touchscreen, IPS, screen size, resolution, CPU, HDD, SSD, GPU, and operating system.

## Dataset
The dataset used for training the model has the following shape: (1303, 11). The columns in the dataset are as follows:
•	Company: Brand of the laptop.
•	TypeName: Type of the laptop.
•	Inches: Size of the laptop screen.
•	ScreenResolution: Resolution of the laptop screen.
•	Cpu: CPU information.
•	Ram: RAM size in GB.
•	Memory: Memory details.
•	Gpu: GPU information.
•	OpSys: Operating system.
•	Weight: Weight of the laptop.
•	Price: Target column (laptop price).

## Algorithm and Model Performance
The Random Forest algorithm was used for building the laptop price prediction model. The model achieved an R2 score of 0.88, indicating a good level of accuracy in predicting laptop prices.

## Project Structure
•	app.py: Frontend code written using Streamlit library.
•	pipe.pkl: Pickle file containing the trained Random Forest model.
•	df.pkl: Pickle file containing the preprocessed dataset.

## Screenshots
Here are some screenshots of the Laptop Price Predictor application:
 
![Capture](https://github.com/guptamrunalini/Laptop-Price-Predictor/assets/113275331/865184ab-55bf-45cd-a144-384b4def3129)

![Capture2](https://github.com/guptamrunalini/Laptop-Price-Predictor/assets/113275331/7796e9e2-582f-4250-8ecd-546b0fe6bec9)

  
## Conclusion
The Laptop Price Predictor project demonstrates the use of machine learning techniques to predict the prices of laptops based on their specifications. By leveraging the Random Forest algorithm, the model achieves a high level of accuracy in estimating laptop prices. The provided Streamlit frontend allows users to input the features of a laptop and obtain an instant prediction of its price. 

