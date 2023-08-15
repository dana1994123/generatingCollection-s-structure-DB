# New Database Structure - Vehicle Collection Initialization

The "NewDBStructure.ipynb" IPython notebook outlines the process of initializing a new vehicle collection based on a real dataset sourced from [Kaggle](https://www.kaggle.com). This dataset provides essential fields such as VIN, make, model, and year, while additional fields are generated following standard conventions. Additionally, the notebook generates OBD-II parameter sets, associates vehicles with users and dealers, and establishes a comprehensive database structure.

## Initialization of Vehicle Collection

In this section, the notebook demonstrates the creation of a new vehicle collection using a real dataset from Kaggle. The dataset contains vital vehicle information, including VIN, make, model, and year. To complete the dataset, the notebook generates other fields using standardized conventions, ensuring consistency across entries.

## OBD-II Parameter Set Generation

The notebook utilizes a predefined `logParamSet` list, derived from the OBD-II standard parameters. Each vehicle in the collection is assigned a set of 17 parameters, including 9 parameters related to EV batteries (common to all vehicles) and 8 randomly selected parameters. This ensures a comprehensive and diverse dataset representation.

## User and Dealer Association

For each vehicle entry, the notebook establishes associations with a user and a dealer. These associations are achieved by incorporating user and dealer information, including email addresses, into the dataset. This enables efficient tracking and management of vehicle ownership and dealership relationships.

## Dealer Collection Initialization

The notebook includes a dealer collection initialization process. This collection is populated using a CSV file containing randomly collected dealer information. Each dealer entry comprises relevant details that facilitate effective management of dealership-related data.

## User Collection Initialization

Similar to the dealer collection, the user collection is also initialized based on a CSV file. This file contains user-related information necessary for accurate user management within the database structure.

## Credential Collection

The credential collection is established to manage user roles within the system. This collection contains records for 22 users, 11 dealers, and 2 administrators. Proper access controls and permissions can be applied based on these user roles.

## Usage

1. Open the "NewDBStructure.ipynb" notebook using Jupyter or a compatible environment.
2. Execute the notebook cells sequentially to witness the creation of the new vehicle collection, generation of OBD-II parameter sets, user and dealer associations, dealer collection initialization, user collection initialization, and credential collection setup.
3. Review the generated data, associations, and collections to ensure they align with the intended structure.

Please note that this README serves as a concise overview. Refer to the actual notebook for in-depth code explanations, implementation details, and data manipulation procedures.

Feel free to contribute, offer feedback, report issues, or suggest enhancements. Your contributions are valued and appreciated.

---

**Author:** Dana Aljamal
**Contact:** danaaljamal94@gmail.com
