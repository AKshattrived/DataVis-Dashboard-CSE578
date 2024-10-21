VAST CHALLENGE 2021 - Kronos Incident MCII

Team members :
 1. Niranjana Suresh
 2. Kush Gosalia
 3. Akshat Trivedi
 4. Gaurav Gondane
 5. Meenakshi Rajesh
 6. Aditya Madabhushi

GASTech, a company with employees managed through the Kronos system and utilizing company cars for both personal and professional use, is currently grappling with the perplexing disappearance of some of its workforce. To unravel the mystery, we leverage credit card and loyalty card transaction data, coupled with GPS information from the employees' vehicles. Through the implementation of interactive visualizations, we aim to discern anomalous patterns in the data and uncover insights that may shed light on the disappearance of GASTech employees. Our approach involves utilizing various visualizations such as histograms, node graphs, heatmaps, and more to identify and understand the behaviors of the employees. By analyzing credit and loyalty card datasets, we pinpoint popular locations and the times they are frequently visited. Additionally, we identify card owners and explore potential informal or unofficial relationships among GASTech employees. The goal is to reveal any irregularities or suspicious activities that could provide answers to the challenges posed by the mysterious disappearance of GASTech personnel.

To tackle the challenge, six visualizations have been implemented. The first one is a Heatmap, displaying transactions across different locations. Upon clicking the heatmap boxes for a specific date, the corresponding bar-pie chart, network graph, and bubble network bar chart become visible. The bar-pie chart depicts the distribution of people across various employment types, and it includes bars atop each sector of the pie chart, indicating the transaction amount for each employee.

The network graph illustrates relationships between employees, where each node represents an employee and edges signify connections between them. The Bubble Network Bar chart shows the amount spent by each person and their employment type for the selected day. Clicking on nodes in the network graph reveals a histogram illustrating credit/loyalty card expenditures for each employee, with the selected employee highlighted.

Moreover, the dropdown for Time Series specifies the attribute selected on the y-axis. The time series chart is then generated for the chosen employee, with the selected date highlighted as a red circle.

To run the code, clone the repository and run the index.html using liveserver.