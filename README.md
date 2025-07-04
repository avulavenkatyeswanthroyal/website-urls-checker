Website Uptime Checker & Screenshot Capturer

This project checks if a list of websites are up and running using Playwright.
If a website is accessible, it takes a screenshot and saves it.
If it's down (timeout or HTTP error), it logs the error.


Features

Checks multiple websites
Takes full-page screenshots if the site is up
Logs errors to a file if the site is down or slow
Organizes results by timestamped folders

 How to Use

Download the files

* url_screenshot_audit.exe
* The URLs.xlsx file (containing the list of websites to check)

 Place both files in the same folder

Make sure your folder looks like:

your-folder/
 ├── url_screenshot_audit.exe
 └── URLs.xlsx


Run the program

 Double-click `url_screenshot_audit.exe
  
What happens

* The tool will start running in the terminal / command prompt.
* It will read URLs from URLs.xlsx, check each website for uptime, and attempt to take screenshots.
* Progress and results are displayed live in the terminal.

5️⃣ *Output*

* A new folder will be automatically created with:

   screenshots/
   - Success        # Screenshots of successfully loaded sites
   -  Error         # Screenshots of Errored sites
  errors.log        # Log file listing sites that failed or returned errors

* Each run creates a separate timestamped folder.


* Make sure you have a stable internet connection for accurate checks.
* Keep the terminal open until the program finishes to see live results.
