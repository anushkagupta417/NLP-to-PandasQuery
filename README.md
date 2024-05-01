# Enhanced Data Analysis by Natural Language Query Processing

This project enables non-technical users to perform data analysis by inputting natural language queries. Our tool interprets these queries, accesses the appropriate data, and provides the results directly to the user. This simplifies the data analysis process, allowing users to focus on insights rather than on mastering query languages and database specifics.

## Features

- **Data Upload**: Users can upload data in CSV or TXT format.
- **Natural Language Processing**: Converts user input from natural language to SQL-like commands.
- **Data Export**: Users can export results in Excel format.
- **Simple User Interface**: Designed for ease of use without prior experience in data querying.
- **Offline Functionality**: Works without needing an online connection.
- **Cross-Platform**: Available for use across different operating systems.
- **Scalable Model**: Efficiently handles small to large datasets.

## Tools Used

- **Pandas**: For data manipulation and analysis.
- **PyTorch**: Utilized for building the underlying machine learning models.
- **Regular Expressions**: For parsing and transforming text data.
- **Streamlit**: For creating and hosting the web interface.
- 

To run the project

```bash
streamlit run main.py
```

## Usage

1. Start the application using Streamlit.
2. Upload your data file in a supported format (CSV or TXT).
3. Enter your query in natural language into the provided text field.
4. Press the "Execute Query" button to process your query.
5. View the results directly in the interface or download them as an Excel file.

## Example Queries wrt titanic dataset

- "Which class has average age less than 45?"
- "Show the number of passengers in each class."
- "Show the number of passengers in each class."
- "Find the name and age of male passengers with age greater than 35."

