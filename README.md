# GetStocksWinForms

A Windows Forms application to fetch and download stock content from [Getstocks.net](https://getstocks.net/). This tool allows users to input links, retrieve information, and download files efficiently.

## Features
- **Link Input**: Enter single or multiple URLs (up to 50) to process.
- **Token Management**: Save and load an access token for API authentication.
- **Download Support**: Fetch stock details and download files from supported links.
- **User-Friendly Interface**: Simple design with success/failure tracking.

## Prerequisites
- **Operating System**: Windows 10 or later.
- **.NET Runtime**: [.NET 9.0 Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/9.0) must be installed to run the application.

## Installation
1. **Download the Release**:
   - Go to the [Releases](/releases) page.
   - Download the latest `GetStocksWinForms_v1.0.zip` file.

2. **Extract the ZIP**:
   - Unzip the downloaded file to a folder of your choice (e.g., `C:\GetStocksWinForms`).

3. **Run the Application**:
   - Double-click `GetStocksWinForms.exe` in the extracted folder to launch the app.

## Usage
1. **Set Access Token** (Optional):
   - Go to `Settings` > `Set Token`.
   - Enter your Getstocks.net API token and click `Save Token`.
   - The token will be saved in `getstocks_token.json` for future use.

2. **Input Links**:
   - Enter one or more URLs (max 50) in the text box, one per line.
   - Alternatively, click `Browse` to load links from a `.txt` file.

3. **Process Links**:
   - Click `Get` to fetch information or download files.
   - For a single link: Details (provider, ID, name) will display with a `Download` button.
   - For multiple links: Success and failure results will show in separate lists.

4. **Download Files**:
   - For single links, click `Download` to save the file.
   - For multiple links, files are downloaded automatically to the `getstocks` folder.

## Screenshots
*(Optional: Add screenshots here by uploading images to the repo and linking them, e.g., `![Main Interface](screenshots/main.png)`)*

## Building from Source
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/[YourUsername]/GetStocksWinForms.git
   cd GetStocksWinForms
