Imported libraries:
I brought in pandas (for handling the dataset), numpy (for numerical operations), matplotlib.pyplot (for plotting), and seaborn (for advanced visualizations).

Loaded the dataset:
I used pd.read_excel("Task2_data.xlsx") to read the Excel file into a DataFrame called df.

Checked the data:
I printed out df to see the first few rows of the dataset, which includes columns like uniqueID, risk, educ, age, sex, kids, and late.

Created a bar plot:
Using Seaborn’s sns.barplot, I plotted the average risk score (y = 'risk') against education level (x = 'educ').

I set errorbar=None so no error bars would be shown.

I gave the chart a title: "Average Risk score by education level".

I labeled the y-axis as "Mean Risk Score".

Displayed the graph:
Finally, I called plt.show() to render the plot.

<img width="1249" height="929" alt="Screenshot 2025-09-22 133214" src="https://github.com/user-attachments/assets/bc4e39ee-43bf-433f-9496-625f6236ce4e" />
