# Description
This project automates the process of converting markdown-formatted meeting notes into a structured Google Doc using the Google Docs API. The script, designed to run in Google Colab, applies proper formatting such as headings, bullet points, checkboxes, and mentions, helping teams streamline documentation workflows.

# Setup Instructions

### Clone the Repository:

- git clone <repository-url>
- cd <repository-folder>

### Open in Google Colab:

Upload the script to Google Colab or open it directly from GitHub using:

from google.colab import drive
drive.mount('/content/drive')

### Authenticate Google API Access:

Run the authentication cell in the Colab notebook to connect your Google account

# Required Dependencies

- Make sure the following dependencies are installed in the Colab environment:

  pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client

# How to Run in Colab

### Upload the script to Colab or access it via GitHub.

### Run the script cells sequentially:

- Authenticate your Google account.

- Convert markdown content to Google Docs.

- View the link to the created document.

### Modify the markdown content as needed in the script.

Once executed, the Google Doc URL will be displayed, containing the formatted meeting notes.
