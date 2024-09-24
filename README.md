# pidinst
**Pilot for Instrument Persistent Identifiers (PIDs) in JHU Labs**

This project automates the minting of Digital Object Identifiers (DOIs) for instruments at Johns Hopkins University (JHU) using the DataCite API. The project is designed to help manage and assign unique identifiers for instruments within JHU labs, including PARADIM, MCP, and the Malone SEM. This tool simplifies the process by integrating with an Excel and Google Form-based workflow.

## Usage 
1. upload excel file
2. edit datacite-api-config.json with DataCite API credentials
3. run jupyter notebook to automate the minting of DOIs:
   the notebook will read the data, call the DataCite API, and update the Excel with newly minted DOIs.

## Key Features and Skills Demonstrated
- **Python Programming**: Automated the workflow using Python, showcasing skills in scripting, data manipulation, and API integration.
- **API Integration**: Integrated the DataCite API to mint DOIs, demonstrating proficiency in handling RESTful API requests and responses.
- **JSON and Configuration Management**: Managed configuration settings through JSON files, enabling secure and flexible API access.
- **Error Handling and Logging**: Implemented robust error handling and logging mechanisms to ensure reliable data operations and maintain detailed records of actions.
- **File and Directory Management**: Automated file and directory creation, ensuring organized storage of metadata and log files.
