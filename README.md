# Order Tracking Incremental Load | Modern Data Engineering Project on GCP

## Introduction
This project aims to develop a robust and efficient order tracking system on GCP using Databricks and Cloud Storage. By leveraging these powerful tools, we will implement an incremental loading process to capture and update order data in real-time, ensuring timely insights into order status, customer behavior, and operational performance.

## Workflow
![Project Workflow](https://github.com/saivinithv/order-tracking-incremental-load-project-/blob/main/Workflow%20of%20order%20tracking.drawio.png)

## Technology Used
1. Programming Language - Python
2. Google Cloud Platform
   - Databricks
   - Cloud Storage(Buckets)
3. Draw.IO (modern data pipeline tool)

## Dataset Used
An order tracking dataset is a collection of information related to individual orders placed within a business or organization. This dataset is essential for businesses to track the progress of orders, manage inventory, and provide accurate customer service. It can also be used for analytics purposes to identify trends, optimize operations, and improve customer satisfaction.
This dataset typically includes details such as:
- Order ID: A unique identifier for each order.
- Customer Information: Details about the customer who placed the order, including their name, address, and contact information.
- Order Date and Time: The date and time when the order was placed.
- Order Status: The current status of the order, such as "pending," "processing," "shipped," "delivered," or "canceled."
- Order Items: A list of products or services included in the order, along with their quantities and prices.
- Shipping Information: Details about the shipping method, shipping address, and expected delivery date.
- Payment Information: Information about the payment method used, payment status, and transaction details.

Here is the dataset used: https://github.com/saivinithv/order-tracking-incremental-load-project-/tree/main/data

## Scripts for the project
1. [stage_data_load](stage_data_load.ipynb)
2. [target_data_load](target_data_load.ipynb)
