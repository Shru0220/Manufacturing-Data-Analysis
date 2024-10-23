
# Manufacturing Process Analysis

**Overview**

This project focuses on analysing the manufacturing process of a clothing/fabric factory using data from various stages of production. The dataset includes information on work orders, buyers, Customers, employees, machine details, machine usage, production quantities, processed quantities, rejected quantities and time metrics such as start and end times of machines. The goal is to uncover insights into production efficiency, machine utilization and operational/cost efficiency. 

The tools used include **Excel**, Power Query and **Power BI** for data visualization and analysis. The charts created help to gain insights into the efficiency of production and pinpoint areas for improvement.

**Key analysis that were performed:**
- Machine cost efficiency
- Rejected quantities by machines and employees
- Processing time and efficiency
- Employee efficiency 
- Production performance and waste

![Screenshot 2024-10-23 120936](https://github.com/user-attachments/assets/4d3132f5-eab3-455f-82a9-de54e8db2958)



**1. Machine Cost Efficiency**

 - **Clustered Bar Plot (Machine Code vs. Rejected Quantity and Per Day Machine Cost)**
- This chart uses a clustered bar plot with Machine Name on the X-axis and two measures on the Y-axis: Sum of Rejected Quantity and Total Per Day Machine Cost.
- A slicer is added to filter the data by **Operations (such as Cut-folding, weaving, etc.)**, allowing for detailed views of different types of production processes.
- A summary table is placed below the chart, which includes **Machine Code, Employee Code and Name, Total Processed Qty, Total Rejected Qty, and Wastage Percent** for each machine.

![Screenshot 2024-10-23 155816](https://github.com/user-attachments/assets/e24a9ff8-69ee-4447-b74e-c09e0de8733a)

*Insights:*

**Machines with higher rejected quantities tend to incur higher costs, which is highlighted by machines like MC025.** This points to inefficiencies in certain machines that may need maintenance or better calibration.

The slicer allows for an in-depth view of specific operations. For example, during the Cut & Fold operation, the rejection rates are highest on certain machines, suggesting the need for focused improvements in that stage of the process.



**2. Processing Time Analysis**

- **A calculated column** was created in Power BI to calculate the processing time in hours, giving insight into how efficiently machines and employees complete their assigned tasks.

*Insights:*

- Processing times of machine were generally consistent, with some spikes that indicated potential delays. 
- The wastage percentage shows some machines have more significant rejection rates, indicating a need for maintenance or review of the operation method or review the employee handling the machine.



**3. Rejection Rates by Machine**
- Bar Chart (Rejected Quantity by Machine Code)
- This bar chart displays the **total Rejected Quantities for each Machine Code**, making it easy to identify which machines are contributing the most to defective output.

![Screenshot 2024-10-23 120726](https://github.com/user-attachments/assets/e58d76f3-1081-4be7-811a-66a2421ee7ea)



*Insights:*

The analysis of the data shows that there are quite a number of machines which are responsible for the majority of rejected units. 

We can see, **the machines with code MC025 and MC048 have significantly higher rejection rates** compared to others, which suggests that these machines should be prioritized for maintenance or operator retraining.



**4. Employee Efficiency:**

- Bar Chart (Top 10 Employees by Rejected Quantities)
- This chart shows the **Top 10 Employees with the highest product rejected quantities**. Each bar represents an employee, helping identify those who may need additional training or support.

![Screenshot 2024-10-23 120748](https://github.com/user-attachments/assets/c5a6ed30-f09c-496a-aecc-db67d9d0685f)


*Insights:*

Highlighting employees with high rejection numbers can help the company management to focus on considering the reasons for such huge rejected quantities and plan for further improvement. 

**Employee EM144 has a significantly high rejection rate as compared to other rejections**. This might indicate a need for further training of the employee or process improvements in their shifts. –



**5. Machine Cost and Rejection Analysis by Employee**

- Clustered Bar Plot (Machine Name vs. Rejected Quantity and Per Day Machine Cost)
- From this chart it was analysed as to how individual employees impact both **production cost and rejection rates**. This compares the Sum of Rejected Quantities and the Total Per Day Machine Cost for each machine combined with a slicer to filter by Employee Code. This allows for analysis the performance of each employee and how much machines does each one handle.
- **A table summarizing data by employee is included below the chart showing Employee Code, Name, Rejected Quantities, and Wastage Percent.**


![Screenshot 2024-10-23 120820](https://github.com/user-attachments/assets/7ce55e2e-546e-44ea-83ff-49bdf88f9fc7)


*Insights:*

Some machines are associated with high rejected quantities with high costs. This can be co-related with the employee as well. This correlation suggests that machine handling or setup might differ between operators, which can directly or indirectly affect the output quality and machine efficiency.

The  Employee Code slicer helps to filter the data for individual employees, making it easy to identify those who are working efficiently and those who may need additional training.



**Conclusion**

- From the analysis we can infer that, various inefficiencies are indicated by certain machines be it their time durations, i.e. having lengthy processing times or the volume of rejected quantities. By looking into these more, overall production efficiency can be increased.
- High machine operational costs and rejected quantities are clearly correlated, indicating that some machines could need maintenance or improved calibration.
- Some of the machines account for the majority of the rejection quantities. These need to be given top priority for upkeep or evaluation of their operations.
- There is a definite relation between certain employee and higher product rejection volume. This suggests the need for more focused training for staff members or additional assessment of machine operator.
