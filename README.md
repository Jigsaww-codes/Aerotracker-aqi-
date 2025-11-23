AeroTrack -- Real-Time Air Quality Monitoring

## Overview

AeroTrack is a Python-based tool that retrieves real-time Air Quality
Index (AQI) and pollutant data using the OpenWeatherMap API. It converts
a place name into geographic coordinates and displays a detailed
environmental report.

## Features

-   Real-time AQI fetching
-   Detailed pollutant concentration report (CO, NOâ‚‚, Oâ‚ƒ, SOâ‚‚, PM2.5,
    PM10, NHâ‚ƒ)
-   Human-friendly AQI interpretation
-   Error handling for invalid inputs and API failures
-   Clean and structured console output

## Technologies Used

-   *Python 3*
-   *requests* library
-   *OpenWeatherMap Geocoding API*
-   *OpenWeatherMap Air Pollution API*

## Installation & Setup

1.  Install Python 3.x\

2.  Install required dependencies:

        pip install requests

3.  Insert your OpenWeatherMap API key inside the script:

     python
    API_KEY = "your_api_key_here"
    

4.  Run the program:

        python 01.py

  ##  Usage:

Run the script and enter any place name when prompted:

    Enter place name: Mumbai

The program will display the AQI and pollutant levels.

## Testing Instructions:

Test with: - Valid places (e.g., Delhi, London) - Small towns (e.g.,
Lonavala) - Invalid entries (e.g., asdasdasd) - Names with spaces or
hyphens (e.g., New York, Rio-de-Janeiro)

## Screenshots
<img width="1644" height="916" alt="Screenshot 2025-11-23 152330" src="https://github.com/user-attachments/assets/96af20de-ebad-4389-9dc3-3c8480230f84" />
<img width="1557" height="916" alt="Screenshot 2025-11-23 152405" src="https://github.com/user-attachments/assets/d5bfaae5-ca45-4303-9bf1-13659a20a526" />
<img width="1418" height="807" alt="Screenshot 2025-11-23 152434" src="https://github.com/user-attachments/assets/f0b79cb8-b208-4fa6-9bf7-01995318a38d" />
<img width="1606" height="677" alt="Screenshot 2025-11-23 152855" src="https://github.com/user-attachments/assets/bde7af5b-160a-4381-91b3-cb05fbbdad63" />


