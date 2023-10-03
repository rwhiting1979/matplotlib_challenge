# Mouse Study Data Analysis
### Overview
This project involves the analysis of data from a mouse study that investigates the effects of different drug regimens on tumor growth in mice. The analysis is conducted in a structured manner, breaking down the tasks into key components to gain insights into the study's findings.

### Project Structure
The project is structured into several tasks, each contributing to a comprehensive analysis:

### Task 1: Data Preparation
In this initial step, the data is prepared for analysis. Data from mouse_metadata.csv and study_results.csv is imported and merged into a single DataFrame. Duplicate time points for certain mouse IDs are identified and removed, ensuring data integrity.

### Task 2: Generate Summary Statistics
Summary statistics for tumor volume are calculated for each drug regimen. This includes mean, median, variance, standard deviation, and SEM. These statistics provide a central overview of tumor volume characteristics across treatments.

### Task 3: Create Bar Charts and Pie Charts
Visualization is a crucial part of data analysis. Two bar charts are generated to visualize the total number of rows (Mouse ID/Timepoints) for each drug regimen. Additionally, two pie charts illustrate the distribution of female versus male mice in the study.

### Task 4: Calculate Quartiles, Find Outliers, and Create Box Plots
Quartiles and IQR are calculated for four promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Potential outliers are identified and highlighted in box plots. This helps understand the spread of final tumor volumes for each treatment.

### Task 5: Create a Line Plot and a Scatter Plot
Line plots visualize tumor volume changes over time for a single mouse treated with Capomulin. A scatter plot explores the relationship between mouse weight and average observed tumor volume across all mice in the Capomulin regimen.

### Task 6: Calculate Correlation and Regression
Correlation coefficients are calculated to assess the relationship between mouse weight and average tumor volume for Capomulin treatment. A linear regression model quantifies this relationship and provides insights into how mouse weight affects tumor volume.

### Task 7: Final Analysis
The project concludes with a summary of findings and insights. The analysis enhances our understanding of the effects of drug regimens on tumor growth and the relationship between mouse characteristics and tumor volume.

## Conclusion
This mouse study data analysis demonstrates the power of data analysis in biomedical research. It allows researchers to extract valuable insights from complex datasets, aiding in informed decision-making and furthering scientific understanding. The structured approach used in this project ensures a thorough exploration of the data and the presentation of key findings.
