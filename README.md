# Multi-Channel Identity Verification Tool

## Project Description

The Multi-Channel Identity Verification Tool is a versatile Python tool designed to enhance user verification processes, intended for use with a whitelisted contact information database. Leveraging SMS text messages, phone calls, and email, it ensures secure and efficient identity verification. This tool is particularly beneficial in mitigating social engineering attacks on Tier 1 technical support agents, improving security and user trust. With options for customization and scalability, it adapts to unique organizational needs. Open-source and transparent, it encourages community collaboration and code review, offering reliability and transparency. In summary, this script is a valuable addition to your cybersecurity toolkit, reducing human error, and providing a robust defense against unauthorized access.

## Prerequisites

Before using this script, ensure that you have the following prerequisites:

- A Twilio account with an Account SID and Auth Token.
- A Twilio phone number for sending SMS and making phone calls.
- A Gmail account for sending emails.
- Python installed on your system.

## Usage

1. **Set Up Twilio:**

   - Obtain your Twilio Account SID and Auth Token from the [Twilio Console](https://www.twilio.com/console).
   - Create a Twilio phone number to use for sending SMS and making phone calls.

2. **Configure Gmail:**

   - Set up your Gmail account for sending emails. Make sure to use the sender's email address and password.
   
3. **Run the Script:**

   - Run the script in your terminal or code editor.
   - Select the type of message you want to send (SMS, Phone Call, or Email) by entering '1', '2', or '3' when prompted.
   - The script will generate a random verification code.
   
4. **Sending Verification Code:**

   - **SMS Text Message:**
     - Enter the destination phone number.
     - The script will send an SMS with the verification code using Twilio's SMS service.
   
   - **Phone Call:**
     - Enter the destination phone number.
     - The script will make a phone call with the verification code using Twilio's voice service.
   
   - **Email:**
     - Enter the destination email address.
     - The script will send an email with the verification code using your Gmail account.

## Important Note

- Ensure that you have replaced `'account sid here'`, `'auth token here'`, `'sender email'`, and `'email sender password'` with your actual Twilio and Gmail credentials in the script.

- Make sure you have set up your Gmail account to allow less secure apps if required.

- Review Twilio's pricing details as charges may apply for using SMS and phone call services.

## Example

Here's an example of running the script:

