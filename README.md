# ScrapeMaster

ScrapeMaster is a Streamlit-based web scraping application designed to simplify the process of extracting data from web pages. It allows users to specify URLs and data fields interactively, facilitating the extraction and manipulation of web data.

## Features

- Easy-to-use web interface.
- Custom field specification for data extraction.
- Pagination
- Dynamic data processing with Python and Streamlit.
- Direct download capabilities for extracted data in various formats.
- Attended mode

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.6 or higher
- Pip for managing Python packages

## Installation

Follow these steps to get your development environment running:

```bash
# Clone the repository
git clone https://github.com/reda-marzouk608/scrape-master
cd scrape-master

# It's recommended to create a virtual environment
python -m venv venv
# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On MacOS/Linux
source venv/bin/activate

# Install the required packages
pip install -r requirements.txt
```

### Streamlit opt-out configuration (optative)

Setting global config file:

- Linux/macOS:

  ```bash
  # create directory if it doesn't exists
  mkdir -p ~/.streamlit/
  # Setting global config file
  cp ./.streamlit/config.toml ~/.streamlit/config.toml
  ```

- Windows:

  ```powershell
  # create directory if it doesn't exists
  $targetDir = "$env:USERPROFILE\.streamlit\"
  if (-not (Test-Path -Path $targetDir)) {
     New-Item -ItemType Directory -Path $targetDir
  }
  # Setting global config file
  Copy-Item -Path ".\.streamlit\config.toml" -Destination $targetDir
  ```

## Launching the Application

To run ScrapeMaster, navigate to the project directory and run the following command:

```bash
streamlit run streamlit_app.py
```

## Usage

After launching the application, open your web browser to the indicated address (typically <http://localhost:8501>). Use the sidebar to input the URL and fields you wish to scrape, then click the "Scrape" button to see results.

## References

- <https://www.youtube.com/watch?v=YCicort0TrQ&ab_channel=RedaMarzouk>
- <https://www.youtube.com/watch?v=ncnm3P2Tl28&ab_channel=RedaMarzouk>
