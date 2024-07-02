# Bulk Email Sender & Undelivered Email Checker

This is a Streamlit web application for sending bulk emails and monitoring undelivered emails using Python.

## Overview

This application allows you to:
- Upload CSV or Excel files containing email addresses and email contents (subjects and bodies).
- Send bulk emails to recipients specified in the uploaded file.
- Monitor undelivered emails using IMAP, particularly those rejected by the mail server.
- Update the original email addresses file with undelivered emails for further action.

## Requirements

Ensure you have Python installed. Install the necessary dependencies using:

```bash
pip install streamlit pandas smtplib openpyxl
```
## Usage
- Upload Email Addresses File: Upload a CSV or Excel file containing a list of email addresses.
- Upload Email Contents File: Upload a CSV or Excel file containing email subjects and bodies.
- Send Emails: Click the "Send Emails" button to initiate sending bulk emails.
- Monitor Undelivered Emails: Start monitoring undelivered emails by clicking the respective button.
## Dataset
-The Dataset folder contains sample CSV files for testing purposes.

## Instructions
Clone the repository:

Copy code
```bash
git clone https://github.com/devaprakash888/Email-Dispatcher-with-Spam-Detection.git
cd your-repo
```
## Run the application:
Copy code
```bash
streamlit run app.py
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.
