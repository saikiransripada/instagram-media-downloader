# Instagram Media Scraper
A simple command-line script to download photos, videos and sidecars (album) of an Instagram profile.

- A command-line script that scrapes all photos, videos and sidecars (album) of an Instagram public profile.
- No configuration or sensitive information required.

# Requirements
- Python 3.x

# Usage
1. Clone the repo to your desktop.
2. Install the required packages using `pip3 install -r requirements.txt`
3. Run the script using the command `python3 instagram.py -u <instagram_username> -p <path_to_download>`
4. Path parameter is optional. Specify the path if you want to save the media in a specific location. If omitted, it downloads the media to the current working directory.
