# YOUD

### Description

The Python project you have created leverages the `pytube` library to enable users to effortlessly download unlimited video or audio content from YouTube by providing a list of links. The system is designed with simplicity in mind, offering a streamlined process that allows users to download video or audio with just a single click. The code includes an intuitive user interface where users input their YouTube links and select the preferred download option.

### Readme

#### YouTube Video/Audio Downloader

This Python project provides a straightforward solution for downloading video or audio content from YouTube. By utilizing the `pytube` library, it empowers users to download an unlimited number of video or audio files with minimal effort. The application includes a user-friendly interface where users can input YouTube video links and choose between video or audio downloads.

### Dependencies

This project relies on the following Python libraries:

- `pytube`: Used for accessing and downloading YouTube videos.
- `IPython.display`: Utilized for rendering HTML and managing display-related functionalities.
- `ipywidgets`: Enables the creation of interactive widgets in Jupyter Notebooks.
- `os`: Provides functions for interacting with the operating system.

### Usage

1. Install the necessary dependencies by running `!pip install pytube` in your Python environment.
2. Execute the provided Python code within an environment that supports Jupyter Notebooks.
3. Input YouTube video links in the designated area, one link per line.
4. Select the desired download option (Video or Audio) from the dropdown menu.
5. Click the "Download Links" button to initiate the download process.
6. The system will display status messages regarding the download progress.

### Note

- Ensure that the specified download directory (`DOWNLOADS_DIR`) is set according to your preferred destination for downloaded files.
- Any errors encountered during the download process will be displayed in the output area.

Please adjust the `DOWNLOADS_DIR` variable in the code to specify the directory where you want the downloaded video/audio files to be stored. For enhanced usability and further development, consider incorporating error handling, progress indicators, and additional features as needed.

Feel free to further customize the interface, appearance, and functionality to suit your specific preferences or integrate it into larger applications.
