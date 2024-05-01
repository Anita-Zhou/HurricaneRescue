# HurricaneRescue
Hackathon 2023

This website is designed to gather and display rescue information during hurricane season in Houston, providing critical data to help individuals find shelter and support.

Features
- Rescue Information Collection: The website integrates data from the Google Maps API and Twitter API, providing up-to-date information on shelters and aid resources in the Houston area.
- Google Maps API Integration: The Google Maps API displays the locations of shelters and support centers, offering users a visual reference for navigating to these locations.
- Twitter API Integration: The Twitter API monitors real-time updates on social media, aggregating posts related to shelters and emergency services to provide additional information on available resources.

How It Works
- Data Gathering: The Google Maps API pulls shelter locations, while the Twitter API gathers real-time tweets related to rescue information.
- Display: The collected data is presented on the website in an intuitive manner, with map markers indicating shelter locations and a feed displaying relevant tweets.
- Accessibility: The website is designed for easy navigation, ensuring that users can quickly find the information they need during an emergency.

Setup
Clone the repository:
bash
Copy code
git clone <repository_url>
Install necessary dependencies:
bash
Copy code
pip install -r requirements.txt
Run the website:
bash
Copy code
python app.py

Contributing
Contributions to improve the website are welcome. Please feel free to open a pull request or raise an issue to report bugs or suggest improvements.

