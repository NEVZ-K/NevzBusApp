**NevzBusApp**

**Overview**

**NevzBusApp** - is a Streamlit-based application designed to help users filter and view bus data from the RedBus platform. The app provides a user-friendly interface for exploring various bus options based on criteria such as bus type, route, star rating, and price range.

**Features**

- Home Page: Provides an overview of the application and its features.
- Find Buses: Allows users to filter buses by type, route, star rating, and price range.
- Bus Table: Displays the entire bus dataset in a paginated format for easy navigation.

**Requirements**

- Python 3.9 or 3.10
- Required Python libraries are listed in `requirements.txt`

**Installation**

1. Clone the repository:

    git clone https://github.com/NEVZ-K/NevzBusApp.git

2. Navigate to the project directory:

    cd NevzBusApp

3. Install the required packages:

    pip install -r requirements.txt

4. Run the Streamlit application:

    streamlit run NevzBusCSV.py

**Usage**

1. **Home Page**: View basic information about the app.
2. **Find Buses**: Use the sidebar to apply filters and find buses that match your criteria.
3. **Bus Table**: Browse the entire bus dataset in a paginated table.

**Project Structure**

- `NevzBusCSV.py`: The main Python script for running the Streamlit app.
- `aa_rb_data.csv`: The CSV file containing bus data.
- `NevzBusLogo.png`: The logo image used in the app.
- `.streamlit/config.toml`: Streamlit configuration file.
- `requirements.txt`: A list of Python dependencies required by the application.
