# Food-Order-Delivery-System---SQL-Data-Analytics-Project


**Project Report: Food Order Delivery System with Data Analytics**

**Objective**
The primary objective of this project was to enhance the operational efficiency and service quality of a restaurant by implementing an integrated Food Order Delivery System with a strong focus on data analytics. This system aimed to facilitate online ordering and delivery processes, streamline menu management, monitor customer orders, and provide actionable insights for the restaurant's decision-making.

**Problem Statement**
The restaurant faced challenges in managing a growing number of online orders, resulting in data discrepancies and operational inefficiencies. Manual order processing and menu management led to errors and customer dissatisfaction, highlighting the need for an automated solution.

**Proposed Solution**
Our solution revolved around the development of a comprehensive database system to address the restaurant's challenges effectively. Key components of our proposed solution included:

1. **Customer Management:** A unique CUST_ID was generated for each registered customer, ensuring easy identification and tracking.

2. **Database Design:** The system incorporated separate tables for MANAGER and DELIVERY_AGENT, enabling efficient data management for these roles.

3. **Order Processing:** A structured order processing workflow was implemented. When a payment transaction was completed, the order details were automatically inserted into the ORDERS table with a unique ORDER_ID. This ORDER_ID served as a primary key for sales tracking and order management.

4. **Real-time Order Tracking:** The ORDERS, DELIVERY, and DELIVERY_AGENT entities were interconnected to allow real-time tracking of orders. Order status was updated in the ORDERS table, and delivery agents were assigned through the DELIVERY table.

5. **Payment Enhancements:** The introduction of the CUST_WALLET entity provided customers with additional payment flexibility. In addition to traditional card payments, customers could use points from their wallet as needed.

**Results and Impact**
The implementation of the Food Order Delivery System with a data analytics focus resulted in several significant outcomes:

- **Improved Efficiency:** The system streamlined online order management, reducing errors and enhancing the speed of service.
- **Data-Driven Insights:** The system provided valuable insights into customer order patterns, popular dishes, and customer retention metrics.
- **Enhanced Customer Satisfaction:** Visual order confirmation eliminated paperwork and improved customer satisfaction.
- **Sales Analysis:** Sales data became readily available and was easily traceable, aiding in strategic decision-making.
- **Operational Efficiency:** The restaurant could efficiently manage online orders, ensuring a seamless customer experience.

**Conclusion**
The Food Order Delivery System, with its data analytics features, successfully addressed the restaurant's challenges in online order management. It not only streamlined operations but also provided valuable data-driven insights, contributing to enhanced customer satisfaction and improved sales analysis capabilities. The system stands as a testament to the power of data analytics in optimizing restaurant operations.

