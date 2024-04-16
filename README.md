## Calculating-YouTube-Playlist-Duration

This Python project provides a tool to calculate the total duration of a YouTube playlist using the YouTube Data API v3. 

**Features:**

- **Accurate:** Extracts duration information directly from YouTube, ensuring reliable results.
- **Efficient:** Utilizes pagination to handle large playlists effectively.
- **Clear:** Employs regular expressions to parse video durations while accounting for potential variations in time format (e.g., "1H2M3S", "01:02:03").
- **User-Friendliness:** Presents the calculated duration in a clear "hours:minutes:seconds" format, making it easily understandable.
- **Secure API Integration:** Demonstrates best practices by using `.env` for API key storage and proper API call handling.

**Benefits:**

- Helps users estimate the time commitment required to watch a YouTube playlist.
- Useful for content creators planning or managing video series lengths.
- Can be adapted for further playlist analysis (average video duration, categorization by duration ranges, etc.).

**Installation:**

1. **Prerequisites:** Ensure you have Python 3 and `pip` installed.
2. **Clone the repository:** Use `git clone https://github.com/YOUR_USERNAME/Calculating-YouTube-Playlist-Duration.git` (replace `YOUR_USERNAME` with your GitHub username).
3. **Create a virtual environment (recommended):** This helps isolate project dependencies. You can use tools like `venv` or `virtualenv`.
4. **Install dependencies:** Navigate to the project directory and run `pip install -r requirements.txt` (assuming you have a `requirements.txt` file listing project dependencies).

**Usage:**

1. **Create a `.env` file (if not already present):** This file will store your YouTube Data API key securely. Add a line like `YOUTUBE_DATA_API_KEY=YOUR_API_KEY` (replace `YOUR_API_KEY` with your actual key).
2. **Run the script:** Execute `python youtube_playlist_duration.py` (replace with the actual script name if different).
3. **Provide playlist ID:** Enter the YouTube playlist ID when prompted. You can find the playlist ID in the URL (e.g., `https://www.youtube.com/playlist?list=PLKnIA16_RmvbAlyx4_rdtR66B7EHX5k3z` has playlist ID `PLKnIA16_RmvbAlyx4_rdtR66B7EHX5k3z`).
4. **The script will output the total playlist duration in hours, minutes, and seconds.**

**API Key:**

Obtain your YouTube Data API key from the Google Cloud Platform ([https://console.cloud.google.com/](https://console.cloud.google.com/)) and store it securely in the `.env` file.

**Further Development:**

- Explore options for displaying a breakdown of individual video durations in the playlist.
- Consider incorporating user input for playlist selection via URL or ID.
- Investigate potential visualizations of the playlist duration data.

**License:**

This project is licensed under the MIT License: [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT).

**Contribution:**

We welcome contributions to this project. Feel free to fork the repository and submit pull requests.
