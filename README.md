# Outlook: Search For Specific keyword in Email and store Attachments in SharePoint Document library
In this solution, we are going to Automate the Document Management Process into SharePoint with Outlook and Microsoft Flow’s Integration. Whenever you receive an Email into your Inbox Flow will start searching into the Subject and body of the Mail for the Specific keyword we provide, If-Match found it’ll get that Mail’s Attached Document and creates a new File into the SharePoint Document Library.

# Working Procedure

This solution is the Integration of the SharePoint and Outlook Office 365 Integration with the Microsoft Flow, it'll check for the specific keyword for Example 'Invoice' into mail.

This solution checks for the Invoice into the Two steps
  
  Step 1: First it'll check the Subject of the Mail if keyword match found it'll save the Attached Document to the SharePoint Document Library.
  
  Step 2: If match doesn't found into the Subject, It'll further check for Invoice into the Body of Mail, and If there is any match found it'll store the Email's Attachment into the SharePoint Document Library.
  
# Example

Here it's an Example of Mail which has 'Invoice' Keyword into Subject of Mail and saves attached Document into the SharePoint Document Library named Invoice.

Step 1: User get Email which has 'Invoice' keyword into the Subject of the Mail.

![Email with Invoice keyword into the Mail](https://github.com/mindlabco/Outlook--Search-For-Specific-Keyword-in-email-and-store-attachments-in-Document-library/blob/master/Invoice%20keyword.png)

Step 2: Our Solution of Microsoft Flow saves the Attached Email into the Invoice named SharePoint Document Library.
![Invoice named SharePoint Document Library with Mail's Attached Document](https://github.com/mindlabco/Outlook--Search-For-Specific-Keyword-in-email-and-store-attachments-in-Document-library/blob/master/Invoice%20Doc%20Library.png)
