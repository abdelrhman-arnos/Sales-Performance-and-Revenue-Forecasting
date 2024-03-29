# Sales Performance and Revenue Forecasting

## Problem Statement
**Background**: In a dynamic and competitive retail environment, the ability to accurately predict sales performance is essential for strategic planning, resource allocation, and financial management. Accurate sales forecasts enable proactive decision-making, helping to maximize revenue and optimize operational efficiency.

**Business Need**: Our retail business requires a robust sales forecasting model that can predict future sales volumes with high accuracy. This model must account for various factors that influence sales, including seasonal trends, promotional activities, and historical sales data.

**Objective**: To develop a machine learning model that forecasts monthly sales for the next quarter, enabling the business to:
- Prepare accurate financial projections for stakeholders.
- Optimize inventory levels to meet predicted demand without overstocking.
- Align marketing and sales strategies with anticipated customer buying patterns.

**Expected Outcome**: Implementation of a predictive model that provides:
- A forecast of monthly sales with a confidence interval, indicating the reliability of the forecasts.
- Insights into the primary factors driving sales trends.
- Recommendations for strategic actions based on the forecasted sales data.

**Success Criteria**: The project will be considered successful if it achieves the following:
- The model achieves a mean absolute percentage error (MAPE) of less than 10% on the validation dataset.
- The model's forecasts inform decisions that result in a measurable increase in operational efficiency and revenue.
- The business can utilize the model's insights to adjust strategies at least one month in advance of anticipated changes in sales trends.

## Dataset
Sample dataset: [train_data.csv](./datasets/train_data.csv)

The dataset contains the following columns:
- Invoice ID: A unique identifier for a transaction
- Branch: The branch of the retail store
- City: The city where the retail store is located
- Customer type: The type of customer, either member
- Gender
- Product line: The category of products
- Unit price: The price of a single unit of the product
- Quantity: The number of products purchased
- Tax 5%: The tax on the product
- Total: The total price of the product
- Date: The date of the transaction
- Time: The time of the transaction
- Payment: The payment method
- Cogs: Cost of goods sold
- Gross margin percentage: The gross margin percentage
- Gross income: The gross income
- Rating: The customer rating of the product

## Installation and Running
1. Create the Conda Environment:
    1. Open your terminal or Anaconda Prompt.
    2. Navigate to the directory where your `environment.yml` is located.
    3. Run the command: `conda env create -f environment.yml`.
    4. This command will create a new conda environment named `sales-performance-and-revenue-forecasting` with all the specified packages installed.
2. Activating the Environment:
    - Activate the newly created environment by running: conda activate `sales-performance-and-revenue-forecasting`.
3. Opening VSCode:
    - Once the environment is activated, you can start VSCode from the same terminal session by simply typing code . if you are in the project directory. This ensures VSCode uses the correct conda environment.
4. Running Jupyter Notebooks in VSCode:
    - With VSCode opened, you should be able to open and run Jupyter Notebooks. VSCode will automatically detect the conda environment `sales-performance-and-revenue-forecasting` and use it for running notebooks.