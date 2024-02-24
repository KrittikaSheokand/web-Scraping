**Individual Project1:**

Extracted the first 250 unique listing URLs from free section of Craigslist San Francisco Bay Area website. Saved each HTML content to a separate file on disk. 
Read each of the saved HTML files from the disk. Extracted and printed the following details:
Title, URL of first image (if an image exists), Description, Post ID, Posted Date, and Last Updated Date

Automated the process of logging into https://theoldreader.com -
Simulated the login process using Python and appropriate libraries like requests. Created a session object to maintain login state across multiple requests.
Prepared a payload with login credentials and other necessary form data identified from the login page and the network analysis.
Sent a POST request to the login form’s action URL to log in, using the session object.

Verifying Successful Login: After attempting to log in, inspected the cookies saved in the session object to understand the information The Old Reader stores on computer.
Used the session object to access https://theoldreader.comLinks to an external site.Verified successful login by checking for the presence of user information that is only available when logged in.
