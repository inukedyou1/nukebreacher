# Nukebreacher

Nukebreacher is a powerful password brute-force tool designed for penetration testing and ethical hacking. It attempts to crack usernames by trying various password combinations, leveraging a combination of well-known password lists and system-generated randomization for added security.

## Features

- **Password Cracking**: Attempts to crack usernames using a brute-force approach with various password files.
- **Randomized Request Timing**: Reduces the chance of being blocked by changing request rates periodically.
- **Email Notifications**: Optionally sends email updates at specific stages (midway or at the end).
- **Progress Bars**: Visual feedback with colorful progress bars during operation.
- **Customizable Requests**: Option to manually adjust or control the request rate for testing.
- **Real-Time Logging**: Displays detailed logs of password attempts, errors, and other important information in separate colored UI boxes.
- **Response Code Checking**: Verifies the response of each request to check if it's going through. If not, a fallback plan is applied.
- **Statistics Display**: Shows key statistics such as the current password attempt, PPM (Passwords Per Minute), and time estimates.
- **User-Friendly UI**: Includes an interactive UI for easy control, including input prompts and colored text for easy visibility.

# Installation


## **Clone the repository:**

`git clone https://github.com/inukedyou1/nukebreacher.git `

`cd nukebreacher`

## **Set up a Python virtual environment (optional but recommended):**

`python3 -m venv myenv`

`source myenv/bin/activate  # On Windows, use myenv\Scripts\activate`

## **Install the required dependencies:**

`pip install -r requirements.txt
` 
## **Run the powerful script:**

`python3 nbreacher`


 


 




**Usage** 

When you run the script, you'll be prompted for the following:

`Username: Enter the username you'd like to target for the brute-force attack.
Bearer Token (optional): If applicable, enter a bearer token.
Cookie (optional): If applicable, enter a cookie for the session.
Email Updates: You can choose whether to receive email notifications at specific stages of the process.
Password Files: The tool will automatically load the darkweb2017-top10000.txt and fortinet-2021_passwords.txt files, with possible custom password lists coming soon....` 

**Notes**
\
`The tool checks the status of each request and adjusts the request rate to avoid blocking.
For large password lists, you will be prompted to confirm if you wish to proceed at a higher speed.
`

**Requirements**
\
Python 3.x \
requests \
termcolor\
These dependencies are required to run the tool. You can install them using the following command:

`pip install -r requirements.txt`
