# Facebook Post Scraper for Shift Trades (Python)

### Aim
 - This project aims to automatically scan for new shift trade opportunities within a specific Facebook group and notify you via an API call to your phone. It utilizes Python and leverages relevant libraries to achieve this functionality.

### Motivation:
-   Tired of manually checking the group for new shift trades?
-   Want instant notifications on your phone for relevant opportunities?
-   This project automates the process, saving you time and effort.

### Technologies:
-   Programming Language: Python
-   Libraries: Beautiful Soup, Requests, Twilio (for API messaging)
-   Platforms: Facebook, SMS (via Twilio API)

### Features:
-   Scrapes new posts from a specified Facebook group based on configurable keywords.
-   Filters through irrelevant content using conditional logic.
-   Sends notification messages directly to your phone through a customizable API.
-   Offers flexibility to adjust keyword filters and notification preferences.

### Current Status:

-   Project is under development.
-   Basic functionality for scraping and filtering is partially implemented.
-   API integration with Twilio for notification is still to be done.

### How to Use (Please be responsible and respect the group's rules):
1.  Clone this repository.
2.  Install required libraries (`pip install beautifulsoup4 requests twilio`).
3.  Update `config.py` with your Facebook group URL, keywords, and Twilio API credentials.
4.  Run the `scraper.py` script.
5.  The script will continuously check for new posts, filter them based on keywords, and send notifications if matches are found.

### Contributions:

This project welcomes contributions and improvements! Feel free to fork the repository, make changes, and submit pull requests.

### License:

This project is licensed under MIT License. See the `LICENSE` file for details.

### Disclaimer:

This project is not affiliated with Facebook or Twilio. Please use it responsibly and adhere to the specific group's rules and regulations.

### Additional Notes:

-   This readme serves as a starting point. Feel free to customize it further with screenshots, detailed instructions, and progress updates.
-   Remember to update the readme as your project evolves and new features are implemented.
