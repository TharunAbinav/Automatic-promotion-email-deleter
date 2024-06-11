# Automated Gmail Compose Email Script

This Python script uses Selenium and PyAutoGUI to automate the process of composing an email in Gmail. It navigates to the Gmail website, logs in with the provided email and password, clicks the "Compose" button, and then performs a series of mouse clicks to interact with the compose window.

## Prerequisites

Before running this script, ensure that you have the following dependencies installed:

- Python 3.x
- Selenium (`pip install selenium`)
- PyAutoGUI (`pip install pyautogui`)
- Google Chrome browser
- ChromeDriver executable (make sure it matches your Chrome version)

## Setup

1. Download the ChromeDriver executable that matches your Google Chrome version from the official website: https://sites.google.com/a/chromium.org/chromedriver/downloads

2. Extract the ChromeDriver executable and place it in the same directory as your Python script or add its location to the system's PATH environment variable.

3. Open the Python script in a text editor and replace the placeholders `"ENTER YOUR EMAIL"` and `"ENTER YOUR PASSWORD"` with your actual Gmail email address and password, respectively.

4. Adjust the mouse click coordinates (e.g., `pyautogui.click(1226,36)`) according to your screen resolution and the position of the compose window. You may need to experiment with these coordinates to ensure accurate mouse clicks.

## Usage

1. Save the Python script and run it using your preferred Python environment or IDE.

2. The script will open the Google Chrome browser and navigate to the Gmail website.

3. It will enter the provided email address and password to log in to your Gmail account.

4. Once logged in, the script will click the "Compose" button to open the compose window.

5. The script will then perform a series of mouse clicks within the compose window based on the provided coordinates.

6. After completing the mouse clicks, the script will wait for 2 seconds and then close the browser.

Note: Be cautious when running this script, as it will perform mouse clicks on your screen based on the provided coordinates. Ensure that the coordinates are set correctly to avoid unintended actions.

## Customization

You can modify the script to perform additional actions within the compose window by adding more `pyautogui.click()` commands with the appropriate mouse coordinates. You can also adjust the timing or add additional logic as needed.

## Disclaimer

This script is provided as-is, and the author is not responsible for any unintended consequences or damages resulting from its use. Use it at your own risk and ensure that you have the necessary permissions to access and automate the Gmail account being used.

## License

This project is licensed under the [MIT License](LICENSE).
