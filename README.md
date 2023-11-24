### Google Maps Places API Scraper

This Python script serves as a tool to harness the power of the Google Maps Places API, focusing on gathering essential information about diagnostic centers within a specified area. The script is designed to extract key details, including the name, address, phone number, and URL for each diagnostic center located within a defined radius of a user-specified location.

#### Key Components

1. **API Key:**
   - The script relies on a Google Maps API key to authenticate and access the Places API, ensuring seamless data retrieval.

2. **Search Parameters:**
   - Customize the script's behavior by adjusting parameters like `area_name`, `place_keyword`, and `radius_in_km`. This flexibility allows users to fine-tune the search based on specific geographical and keyword preferences.

3. **Data Retrieval:**
   - Leveraging the `googlemaps` Python library, the script interacts with the Google Maps Places API to retrieve comprehensive information about diagnostic centers.
   - Implements a brief pause between API requests to avoid potential rate limits and ensure a smooth data extraction process.

4. **Output:**
   - The script produces a CSV file stored in the `data` directory. This file encapsulates details about the identified diagnostic centers, offering a structured and accessible format for further analysis or reference.

#### Customization and Adaptability

The script is adaptable to various scenarios, allowing users to easily modify parameters to suit their specific requirements. Whether it's exploring different geographical areas, targeting specific types of diagnostic centers, or adjusting the search radius, the script offers a versatile solution for extracting relevant information from the Google Maps Places API.

#### Getting Started

To run the script successfully, users need to obtain a Google Maps API key and set it as an environment variable named `API_KEY` in a `.env` file. Detailed setup instructions can be found in the script's documentation.

Feel free to explore and modify the script according to your preferences, unlocking the potential of the Google Maps Places API for your specific use case.