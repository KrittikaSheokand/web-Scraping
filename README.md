Individual Project1: Extract the first 250 unique listing URLs from free section of Craigslist San Francisco Bay Area website. Save each HTML content to a separate file on disk. 
Read each of the saved HTML files from the disk. Extract and print the following details:
Title: The title of the listing.
URL of first image (if an image exists):  The URL of the displayed image.  It can be found in the `src` attribute of `<img>`
Description: The full description text of the listing.
Post ID: Usually found at the bottom of the page or within the page's HTML structure.
Posted Date: The date when the listing was originally posted.
Last Updated Date: The date when the listing was last updated.

Next, Automate the process of logging into https://theoldreader.com
Simulated the login process using Python and appropriate libraries like requests. Created a session object to maintain your login state across multiple requests.
Prepared a payload with login credentials and other necessary form data identified from the login page and the network analysis.
Sent a POST request to the login form’s action URL to log in, using the session object.

Verifying Successful Login: After attempting to log in, inspected the cookies saved in the session object to understand the information The Old Reader stores on computer.
Used the session object to access https://theoldreader.comLinks to an external site.Verified successful login by checking for the presence of your user information that is only available when logged in.
