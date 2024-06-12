# **Toy Sales Data Analysis**
#### The main objective of this project is to perform regression on the toy brand dataset to predict sales using TV spend and Digital spend variables. 
#
## **Data used**
#### The analysis is perfromed on an Excel file named 'toy_sales_data.xlsx', which contains two sheets:
* Data - two years of monthly historical sales and media investment data, in dollars.
* Planned spend - the amount of investment planned for TV and Digital for the first 3 months of 2018.

#
## **Model**
#### OLS model from statsmodels is used for regression.
* **Independent variables:**
  * TV Spend('tv_spend')
  * Digital Spend('digital_spend')
* **Dependent variable:**
  * Sales('sales')

#
## **Requirements**
#### To run the script, you need to have the following libraries installed:
* pandas
* matplotlib
* statsmodels
* seaborn

You can install these libraries using pip:

```
pip install pandas matplotlib statsmodels seaborn
```

#
## **Results**
* **Correlation Matrix** 
  * **Sales and TV spend:** Correlation is 0.44
  * **Sales and Digital spend** Correlation is 0.66 
  * **TV spend and Digital spend** Correlation is 0.07 
* **Adjusted R-squared**
  * The adjusted R-squared value for the regression model is 0.558616056482552.

* **P-values**
  * **Constant(const):** 0.0000006717198
  * **tv-spend:** 0.009746777
  * **digital_spend:** 0.00016192

* **TV contribution to Sales**
  * **In dollars -** $44,108,224
  * **Percentage -** 16.6%
  * **TV ROI -** 1.73

* **Predicted Sales**
  * **Month 1:** $8,334,056
  * **Month 2:** $9,082,486
  * **Month 3:** $10,892,394
#
## **Files Submitted**
* **toy_sales_data.xlsx** - excel sheet containing sales, tv spend and digital spend data
* **regression.ipynb** - jupyter notebook containing the solution code and outputs
*  **report.pdf** - containing answers to specific questions from the question set 
* **regression.py** - python script file containing entire code
#
## **Execution**
Ensure the Excel sheet (`toy_sales_data.xlsx`) is located in the same directory as the Python file (`regression.py`) and the Jupyter Notebook file (`regression.ipynb`).
### **Running the Python Script**
To run the Python script, use the following command in your terminal:

```
python regression.py
```

### **Running the Jupyter Notebook**
To execute the Jupyter Notebook (`regression.ipynb`), open it in any compatible environment and run the cells.

Both the Python script and the Jupyter Notebook will perform the same analysis and generate the required outputs.



 