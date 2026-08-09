 Customer Inquiry AI Email Automation 

 An AI-powered customer support workflow built in make.com.

 # What it does
 When a customer submits a Google Form:

1.Google Forms captures the new response.
2.OpenAI generates a short, friendly, professional customer-support email.
3.Gmail sends the generated response back to the customer's email.

 # Workflow
 Google Form - OpenAI - Gmail

 1.Google Forms - Watch Responses
 The trigger watches for new responses from a configured Google Form.

 The form response provides:
 -Customer name
 -Customer email
 -Customer interest
 -Customer message

 The original workflow also exposes response metadata such as response ID and submission timestamps.

 2.Open AI - Generates the reply
 The workflow sends the customer's details to an OpenAI module with instructions to:
 -Write a short, friendly and professional email 
 -Keep the response under 100 words
 -Don't invent any unwanted information

 The Blueprint uses gpt-4o-mini and a maximum output of 200 tokens

 3.Gmail - Send the Email
 The generated response is sent to the customer's email address

 Subject: Thank you for your inquiry

 The workflow uses the generated OpenAI text as well as the email content.

 #Why this automation is useful
 This removes repetitive manual work from customer support.

 Instead of a team member reading every form submission and writing a basic response manually, the workflow can:
 -Capture the inquiry automatically
 -Generate a contextual response
 -Send the reply automatically
 -Maintain a consistent support tone

 #Technologies
 -Make.com
 -Google Forms
 -OpenAI API
 -Gmail

 #Setup
 This repository contains a sanitized Make.com blueprint.
 Before importing/using it, reconnect your own:

 -Google Account
 -Google Form
 -OpenAI connection
 -Gmail connection

 The sanitized blueprint intentionally replaces account-specific identifiers with placeholders such as:

 -YOUR_GOOGLE_FORM_ID
 -YOUR_GOOGLE_CONNECTION_ID
 -YOUR_OPENAI_CONNECTION_ID
 -YOUR_GMAIL_CONNECTION_ID


 #IMPORTANT
 The blueprint is a portfolio-safe cop of the original workflow. It preserves the automation structure and mappings while removing account-specific identifiers.

 #PROJECT PURPOSE
 This project demonstrates an end-to-end AI automation use case:
 Customer inquiry - AI generated response - automated email delivery
 

 
