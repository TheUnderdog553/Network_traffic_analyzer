
# Network Analyzer

Network Analyzer is a command-line application that analyzes network traffic data captured in CSV format. It offers functionalities such as displaying data, building and visualizing network graphs, tracing suspected addresses, and finding the geolocation of public IP addresses. This application is designed to work on Windows OS.

## Features

- Show Data: View and analyze traffic data from the CSV file.
- Build Graphs: Generate and display network graphs and bar charts based on traffic data.
- Trace Suspected Address**: Identify and analyze traffic related to a specific suspected address.
- Find Public IP Address GeoLocation: Determine the geographical location of a public IP address using the GeoIP2 database.

## Prerequisites

Before running the application, ensure you have the following:

1. Python: Version 3.x installed on your system.
2. Required Libraries: Install the necessary Python libraries using pip:

   ```bash
   pip install pandas matplotlib networkx pyvis geoip2 pyfiglet
   ```

3. GeoIP2 Database: Download and place the `GeoLite2-Country.mmdb` file in the same directory as the script. This file is used for geolocation lookups.

## Usage

1. Start the Application: Run the `network_analyzer.py` script to start the application.

   ```bash
   python network_analyzer.py
   ```

2. Menu Options:
   - **1. Start**: Load a CSV file with network traffic data and access various analysis features.
   - **2. About**: View information about the application and the developer.
   - **3. Exit**: Close the application.

3. Data Analysis:
   - Show Data: View the first 10 readings, source and destination counts, protocols and counts, or traffic of a specific protocol.
   - Build Graphs: Display network node views, edge views, network maps, or bar graphs of protocols.
   - Trace Suspected Address: Input a suspected address to view related traffic and visualize connections.
   - Find Public IP Address GeoLocation: Enter a public IP address to determine its geographical location.

## Troubleshooting

- File Not Found: Ensure the CSV file path is correct and accessible.
- Permission Error: Run the application with the necessary permissions if encountering file access issues.
- Invalid Input: Follow the input prompts carefully to avoid errors.

## Example

Here is an example of using the application:

1. Start the application and choose option `1` to begin network analysis.
2. Enter the complete path to your CSV file.
3. Navigate through the menu options to analyze data, build graphs, trace addresses, or find geolocation.

## License

This application is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

- **Developer: Priyanshu Singh
- GitHub: [TheUnderdog553](https://github.com/TheUnderdog553)
- LinkedIn: [Priyanshu Singh](https://www.linkedin.com/in/priyanshu-singh-a50a22265)

---

Feel free to adjust the content based on your specific needs and any additional information you'd like to include!
