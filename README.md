<h1>NewDBStructure - Python Script</h1>

<h3>Description</h3>
NewDBStructure is a Python script that manages different collections, including vehicles, dealers, users, and credentials. It processes data from two CSV files: electricVehicle.csv and dealer.csv. The information for the vehicles collection is sourced from electricVehicle.csv, which was obtained from https://www.kaggle.com. The data for dealers is extracted from dealer.csv, which contains random information about 11 dealers in a specific format.

<h3>Data Sources</h3>
electricVehicle.csv: This file provides information about electric vehicles and is sourced from https://www.kaggle.com.
dealer.csv: This file contains random information about 11 dealers, including dealer name, location, contact details, brands, inventory, services, ratings, special offers, and hours of operation.

<h3>Collections</h3>

**Vehicles Collection:** This collection is created using data from electricVehicle.csv. It contains information about various electric vehicles, such as their make, model, year, price, and specifications.

**Dealers Collection:** The dealers collection is generated using the data from dealer.csv. It holds details of 11 dealers, including their names, locations, contact information, available brands, inventory status, offered services, ratings, special offers, and hours of operation.

**Users Collection:** This collection is created based on the data derived from the Dealers Collection and additional user information. It contains details about users who interact with the system.

**Credentials Collection:** The credentials collection is generated using information from the Users Collection. It securely stores user credentials, such as usernames and encrypted passwords.


<h3>Script Execution</h3>
To run the newDBStructure.py script, follow these steps:

Ensure you have Python installed on your system (Python 3.x is recommended).
Download the newDBStructure.py file and the required CSV files (electricVehicle.csv and dealer.csv).
Place all files in the same directory.
Open a terminal or command prompt and navigate to the directory containing the script and data files.
Execute the following command:
python newDBStructure.py

The script will read the data from the CSV files, process it, and populate the collections accordingly.
After execution, you can access the data in each collection programmatically or through appropriate database management tools.

<h3>Dependencies</h3>
The newDBStructure.py script relies on the following Python libraries:

**csv:** For reading and parsing CSV files.
**pandas:** For data manipulation and handling.
**bcrypt:** For secure password hashing and verification.
Ensure you have these libraries installed in your Python environment before running the script. You can install them using pip:

pip install pandas bcrypt

<h3>Disclaimer</h3>
Please note that the data from electricVehicle.csv is sourced from external sites and might be subject to copyright or usage restrictions. Ensure you have proper authorization to use this data for your project. Additionally, the script provided here is for demonstration purposes and may require further customization and error handling for production use.




