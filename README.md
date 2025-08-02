# Automated-Report-Generator
Name:Raj Chaurasiya

Intern Id:CT04DZ1762

Domain Name:Python programming

Duration:4 weeks

Mentor Name:Neela Santosh

Discription:
This project focuses on creating an automated sales reporting system using Python. The primary goal of the script is to read structured sales data, perform insightful data analysis, and generate a well-formatted PDF report summarizing both key statistics and daily sales records. This approach demonstrates the practical use of Python in business automation, data analysis, and document generation.

The dataset used is a simple CSV-formatted string representing 5 days of sales for three products — Widget A, Widget B, and Widget C. Each entry in the dataset includes the date, product name, units sold, and revenue generated. This data is parsed using the pandas library, a powerful tool widely used in data science for its ability to handle structured data efficiently.

The script begins by reading the CSV data using StringIO, allowing the multiline string to be interpreted as file-like input. Once loaded into a DataFrame, the data is analyzed to extract key performance indicators:

Total Units Sold: Calculated by summing the "Units Sold" column across all records.

Total Revenue: Derived from the sum of the "Revenue" column.

Average Revenue per Day: Calculated using the mean of the daily revenue.

Top-Selling Product: Determined by grouping the data by product and identifying the one with the highest total revenue.

These metrics provide a concise summary of overall sales performance and are crucial for quick business decision-making.

To present this data in a professional format, the script uses the FPDF library. A custom PDF class is defined to include a styled header and footer, as well as utility methods for formatting sections with titles and multi-line body text. This structure allows the report to be neatly organized and easy to read.

The PDF report is divided into two main sections:

Summary Statistics — This section presents the total units sold, total revenue, average daily revenue, and the name of the top-performing product.

Daily Sales Records — A detailed log of each day’s sales, showing the date, product sold, units sold, and the revenue earned.

Each section is clearly labeled and styled using basic formatting features of FPDF, ensuring clarity and a clean layout. Finally, the generated PDF report is saved as sales_report_embedded.pdf, ready to be viewed, printed, or shared.

Use Case and Relevance
This project is an excellent demonstration of how Python can be applied in real-world scenarios beyond basic scripting. It shows how to:

Handle CSV data without using external files.

Perform meaningful data analysis using pandas.

Format and automate report generation using FPDF.

Such a system could be integrated into business workflows for generating automated daily, weekly, or monthly reports. It is particularly useful for small business owners, retail managers, and analysts who need to report sales performance efficiently.

Conclusion
In conclusion, this project successfully integrates data analysis and document automation to create a real-world solution. It improves efficiency, ensures consistency, and reduces manual reporting effort. The project highlights the versatility of Python in solving practical problems and showcases essential skills in data handling, reporting, and automation.

