# Regional- Analysis

<img width="716" height="278" alt="image" src="https://github.com/user-attachments/assets/78ba9322-8da4-4f85-81c0-768c6fe6af4f" />


**Dataset information for the Regional Analysis**


This is a project of a company that wants to know what to earn from each region that they are selling their products to. 

The task to be done are; 
Removing Duplicate IDs - so ensure that each ID in the data set is unique identifying and removing any duplicate entries. 

Secondly, Handling Infinite Values-  To identify and drop any rows where the price per unit column contains "inf", has those values are not valid for analysis.

Thirdly, Regional Analysis- To calculate the total quantity sold and total value(Quantity * Price per unit) for each region.



  # Dataset Before Cleaning

  <img width="1340" height="686" alt="Screenshot 2025-08-31 141601" src="https://github.com/user-attachments/assets/77196182-25ea-45ec-8fab-0302e4f8f683" />


# Dataset After Cleaning

<img width="1344" height="686" alt="Screenshot 2025-08-31 164055" src="https://github.com/user-attachments/assets/909481c0-af08-4c76-85b7-6911e24321aa" />

I did some cleaning in the dataset

**I removed the duplicate values**,

**I removed the "inf" values because it's of no use**,

**I added another column to the dataset named **Total Values**, and i got the it by multipling "Quantity" and "Price Per Unit"**


# The Pivot Table

<img width="1364" height="685" alt="Screenshot 2025-08-31 165320" src="https://github.com/user-attachments/assets/a4a3f674-71fb-4607-a0fc-c74b7919027c" />

The **Pivot Table** shows The Total value sold in each region

**Observation From the Pivot Table**

The column **Total Values Per Region** in the **Pivot Table ** is in an ascending order.
And it shows that South Region have the highest value.
