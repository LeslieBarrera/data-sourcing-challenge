# NOAA Space Weather Prediction Challenge

## Background
This project aims to prepare a dataset for the NOAA Space Weather Prediction Center to help predict Geomagnetic Storms (GSTs) caused by Coronal Mass Ejections (CMEs). CMEs are massive bursts of plasma emitted from the Sun that can interact with Earth's magnetic shield, causing geomagnetic storms that may affect electronic devices, satellites, GPS systems, and power grids.

## Objective
The objective is to extract and merge data from NASA's API related to CMEs and GSTs to analyze the time it takes for a CME to affect a GST. This information can later be used to improve predictive models for space weather events.

## Data Sources
- **NASA's DONKI API**: The data for CMEs and GSTs is obtained from NASA's API, which provides detailed information about these solar phenomena.

## Project Structure
- **Data Retrieval**: The project retrieves CME and GST data from the NASA API, processes it, and cleans it for analysis.
- **Data Processing**: The data is merged based on relevant identifiers and time differences are calculated to understand the impact timing between CMEs and GSTs.
- **Results Export**: Finally, the processed data is exported to a CSV file for further analysis or use in machine learning models.

## Requirements
- Python 3.x
- Pandas
- Requests
- JSON

## Usage
1. Clone the repository.
2. Set up your environment and install required libraries.
3. Update your `.env` file with the necessary API key.
4. Run the Jupyter Notebook to retrieve and process the data.

## Acknowledgments
Special thanks to NASA for providing access to the API and the data used in this project.
