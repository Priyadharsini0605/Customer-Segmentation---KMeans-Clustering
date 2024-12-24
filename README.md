
# Customer Segmentation using K-Means Clustering

This project analyzes customer data to perform segmentation using K-Means clustering. The goal is to group customers based on their billing and subscription patterns to derive actionable insights.

## Dataset
The dataset is sourced from Kaggle:
[Telco Customer Churn](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset)

### Key Columns Used
- **Monthly Charges**: The monthly fee paid by the customer.
- **Total Charges**: The total amount billed to the customer.
- **Tenure Months**: The duration of the customer's subscription.
- **Contract**: Type of contract (e.g., month-to-month, yearly).
- **Payment Method**: The method used for payments.
- **Paperless Billing**: Whether billing is paperless or not.

## Clustering Approach
- **K-Means Clustering**: Used to segment customers into four clusters based on the selected features.
- **Feature Scaling**: Data was standardized using `StandardScaler` from `sklearn`.

### Visualization
The clusters are visualized in a scatterplot with:
- **X-axis**: Monthly Charges
- **Y-axis**: Total Charges
- **Color**: Cluster label

## Requirements
- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `kagglehub`

## How to Run
1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `customer_segmentation.py` script.

## Results
The clustering analysis revealed distinct customer segments based on their billing patterns and subscription details.

## Usage
This segmentation can help businesses:
- Target high-value customers.
- Develop personalized marketing strategies.
- Predict customer churn risk.

---

### Sample Visualization
Below is an example of the scatterplot visualization:

![Cluster Visualization](image.png)

---

## License
This project is open-source and available under the MIT License.
