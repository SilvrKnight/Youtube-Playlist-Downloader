```markdown
# YouTube Playlist Downloader 🎥

A powerful and efficient tool for downloading entire YouTube playlists using `yt-dlp`, `tqdm`, and `colorama` for a seamless and visually appealing user experience.

## Features ✨

- **Concurrent Downloads**: Utilize multi-threading to download multiple videos simultaneously, significantly reducing total download time.
- **Download Progress Visualization**: Real-time progress bars for each video download, powered by `tqdm`.
- **Rich Terminal Output**: Enhanced console output with colors for better readability and user interaction, thanks to `colorama`.
- **Customizable Format Selection**: Automatically selects the best available video and audio format for each download.
- **Robust Error Handling**: Gracefully handles errors and provides informative messages to the user.

## Installation 🛠️

### Prerequisites

- **Python 3.6+**: Ensure you have Python 3.6 or higher installed. You can download it from [python.org](https://www.python.org/downloads/).
- **Virtual Environment (Optional but Recommended)**: It is advisable to use a virtual environment to manage dependencies.

### Steps

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/Akanksha54/Youtube-Playlist-Downloader.git
    cd Youtube-Playlist-Downloader
    ```



2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Usage 🚀

### Running the Script

1. **Execute the Script**:
    ```sh
    python3 Playlist-x-Downloader.py
    ```

2. **Enter Playlist URL**: Provide the URL of the YouTube playlist when prompted.
    ```plaintext
    Enter Playlist URL: https://www.youtube.com/playlist?list=PLw-VjHDlEOguPYJj77O4VnmI8KeDjZdms
    ```

3. **Download Process**:
    - The script will fetch playlist details and display the total number of videos.
    - It will start downloading videos concurrently, displaying progress bars for each.

### Example Output

```plaintext
Enter Playlist URL: https://www.youtube.com/playlist?list=PLw-VjHDlEOguPYJj77O4VnmI8KeDjZdms

Playlist: My Favorite Playlist
Playlist contains 15 videos.

Downloading Started...

Thread-1 is downloading: Video Title 1
Thread-2 is downloading: Video Title 2
...
Thread-1 --> Video Title 1 Downloaded at 1.23 MB/s
Thread-2 --> Video Title 2 Downloaded at 1.56 MB/s
...
```

## Authors ✍️

- **SilvrKnight** 
  - GitHub: [github.com/silvrknight](https://github.com/silvrknight)
- **Akanksha**
  - GitHub: [github.com/Akanksha54](https://github.com/Akanksha54)

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

