# 📀 Data Sweeper

## Overview
**Data Sweeper** is a powerful web application that allows users to transform their files between CSV and Excel formats with built-in data cleaning and visualization capabilities. This app is built using Streamlit and Pandas, offering an intuitive interface for data manipulation.

## Features
- **File Upload**: Upload multiple CSV and Excel files.
- **Data Preview**: View the head of the dataframe.
- **Data Cleaning**:
  - Remove duplicate rows.
  - Fill missing values with the mean of the column.
- **Column Selection**: Select specific columns for conversion.
- **Data Visualization**: Simple bar chart visualization for numeric data.
- **File Conversion**: Convert files to CSV or Excel formats.
- **Download Option**: Download the cleaned and transformed files.

## How to Use
1. **Upload Files**: Click on the "Upload your files" button to upload CSV or Excel files.
2. **Preview Data**: The app will display the first few rows of the uploaded data.
3. **Clean Data**: Use the data cleaning options to remove duplicates or fill missing values.
4. **Select Columns**: Choose specific columns you want to include in the final output.
5. **Visualize Data**: Enable data visualization to view a simple bar chart.
6. **Convert Files**: Select the desired output format (CSV or Excel) and click the convert button.
7. **Download Files**: Use the download button to save the transformed files to your local machine.

## Installation
To run this app locally, follow these steps:

### Prerequisites
- Python 3.7 or above
- pip (Python package installer)
- Git

### Steps
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/areeb1777/data-sweeper.git
    cd data-sweeper
    ```
2. **Create a Virtual Environment**:
    ```sh
    python -m venv venv
    ```
3. **Activate the Virtual Environment**:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
4. **Install the Requirements**:
    ```sh
    pip install -r requirements.txt
    ```

5. **Run the App**:
    ```sh
    streamlit run app.py
    ```

## Deployment
To deploy this app on [Streamlit Sharing](https://streamlit.io/sharing):

1. Go to Streamlit Sharing and sign up (if you haven't already).
2. Click on "New App" and connect your GitHub repository.
3. Select the branch and main file (`app.py`).
4. Click on "Deploy" and your app will be live.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Thanks to Streamlit for providing a powerful platform for building web apps.
- Special thanks to [Pandas](https://pandas.pydata.org/) for data manipulation and analysis.

## Contact
For any inquiries, please reach out to [areeb777358@gmail.com](mailto:areeb777358@gmail.com).

---

**Note:** Replace `areeb1777`, `https://github.com/areeb1777/data-sweeper.git`, and `areeb777358@gmail.com` with