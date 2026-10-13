# Mall Customer Segmentation Using K-Means Clustering

## Project Overview
This project demonstrates customer segmentation using the **K-Means Clustering algorithm in IBM SPSS Modeler**. The Mall Customer Dataset is used to group customers based on their characteristics and shopping behavior.

The main purpose of this project is to identify different customer segments that can help businesses improve marketing strategies, provide customized offers, and increase sales.

## Objectives
- Import and explore the Mall Customer Dataset.
- Identify and remove duplicate customer records using `CustomerID`.
- Configure variable measurement levels and roles.
- Apply the K-Means Clustering algorithm to create customer groups.
- View the assigned cluster for each customer.
- Filter the final output to retain only `CustomerID` and `Cluster`.
- Export the final results to an Excel file.

## Tools and Technologies
- IBM SPSS Modeler
- K-Means Clustering
- Mall Customer Dataset
- Microsoft Excel

## Workflow
1. **Data Import:** Import the Mall Customer Dataset and examine the records using a Table node.
2. **Data Cleaning:** Use the Distinct node to remove duplicate records based on `CustomerID`.
3. **Variable Configuration:** Use the Type node to define variable measurement levels and roles. Exclude `CustomerID` from clustering inputs.
4. **Model Building:** Configure and run the K-Means node to generate customer clusters.
5. **Cluster Analysis:** Connect a Table node to view customers with their assigned clusters.
6. **Data Filtering:** Use the Filter node to retain only `CustomerID` and `Cluster`.
7. **Export Results:** Use the Excel Export node to save the final customer cluster assignments.

## Expected Output
The final output contains two fields:

- `CustomerID` – Unique identifier of each customer.
- `Cluster` – Cluster assigned to the customer by the K-Means model.

The exported Excel file can be used to examine customer groups and support targeted marketing decisions.

## Applications
- Customer segmentation
- Targeted advertising and promotions
- Customer behavior analysis
- Personalized marketing strategies
- Business decision-making

## Conclusion
This practical demonstrates how K-Means Clustering can be implemented in IBM SPSS Modeler to segment mall customers. The resulting cluster assignments provide a foundation for understanding customer groups and developing customized marketing strategies.

## Author
Sahil kumar singh
