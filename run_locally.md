

#### Local Run Instructions

To run the Google Maps Places API scraper locally, follow these steps:

1. **Set up Google Maps API Key:**

   Obtain a Google Maps API key and set it as an environment variable named `API_KEY` in a `.env` file in the project directory. The `.env` file should look like this:

   ```
   API_KEY=your_api_key_here
   ```

2. **Install Dependencies:**

   Run the following command to install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Script:**

   Execute the script using the following command:

   ```bash
   python script.py
   ```

4. **Output:**

   The script will generate a CSV file in the `data` directory containing details about diagnostic centers in the specified area.

   ```bash
   Details saved to data/{file_name}
   ```

Adjust the script parameters in `script.py` if needed, such as `area_name`, `place_keyword`, and `radius_in_km`.