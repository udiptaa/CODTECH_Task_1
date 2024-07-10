#CODTECH_TASK_1

Superstore Data Analysis
This project involves analyzing a dataset from a global superstore. The analysis includes cleaning the data, generating descriptive statistics, visualizing the data, and exploring relationships between key variables.

Table of Contents
Installation
Usage
Dataset Information
Descriptive Statistics
Visualizations
Correlation Analysis
License
Installation
To run this project, you'll need to have Python installed along with the following libraries:

pandas
numpy
matplotlib
seaborn
You can install the required libraries using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn
Usage
Clone this repository to your local machine.
Place the dataset (Global_Superstore2[1].xlsx) in the project directory.
Run the Jupyter Notebook or Python script to perform the analysis.
Dataset Information
The dataset used in this project is a global superstore dataset containing various attributes such as Sales, Quantity, Discount, Profit, Shipping Cost, and more. The dataset is loaded using the pandas library and cleaned by handling missing values.

Descriptive Statistics
The descriptive statistics for the dataset are calculated using pandas and NumPy. This includes mean, median, and standard deviation of sales, as well as basic statistics for other numerical columns.

Visualizations
Histograms
Histograms for numerical columns such as Sales, Quantity, Discount, Profit, and Shipping Cost are plotted using seaborn. The histograms are displayed with a golden color theme.

Scatter Plots
Scatter plots are used to identify relationships between key variables, including:

Sales vs Profit
Sales vs Discount
Sales vs Quantity
Profit vs Discount
Profit vs Quantity
Correlation Heatmap
A correlation heatmap is generated to visualize the correlation between numeric columns in the dataset. The heatmap uses a cool-warm color scheme.

License
This project is licensed under the MIT License.



