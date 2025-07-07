![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) 
## File Description

### Main Files

- **Prediction_UAV_energy_consumption.ipynb**  
  Main notebook for predicting UAV energy consumption using the available data.

- **testing_rf.ipynb**  
  Notebook for testing and validating Random Forest models.

- **best_rf.csv**  
  CSV file containing the best results obtained with the Random Forest model.

- **results_rf.csv**  
  Detailed results of the Random Forest model.

- **df_train.csv**  
  CSV file containing the training data used to build the models.

---

### Directory `Data_Mini_Projet_DATA_2025`

This directory contains raw and combined data used in the notebooks:

- **flights.csv**  
  Combination of data available in `flights.zip` and `parameters.csv`.  
  - **Number of variables:** 28  
  - **Number of cases/rows:** 257,896  
  - **Missing data codes:** "NA" (no missing data in this dataset).  
  - **Variable description:**  
    - `flight`: Code of the flight performed.  
    - `time`: Time elapsed during the flight in seconds.  
    - `wind_speed`: Wind speed in m/s.  
    - `wind_angle`: Wind angle in degrees.  
    - `battery_voltage`: System voltage in Volts.  

- **parameters.csv**  
  File containing flight parameters.  
  - **Number of variables:** 7  
  - **Number of cases/rows:** 209  
  - **Missing data codes:** "NA" (no missing data in this dataset).  
  - **Variable description:**  
    - `flight`: Code of the flight performed.  
    - `speed`: Horizontal speed programmed during cruise in m/s.  

- **README.txt**  
  File with detailed documentation about the data and naming conventions.

---

## Additional Notes

- **Relationship between files:**  
  - `flights.csv` combines data from `parameters.csv` and individual CSV files contained in `flights.zip`.  
  - `raw_files.zip` contains raw data collected by each sensor for each flight.

- **Citation:**  
  If you use the data or models from this repository, please cite the main author:  
  - Email: csamaras@cmu.edu  

---

## Contact

For questions or support, contact the main author:  
- Email: csamaras@cmu.edu  