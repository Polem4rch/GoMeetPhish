# GoMeetPhish
Google Meet Phishing Template For Gophish



Disclaimer: All information to use for “Ethical Hacking” purpose respectively,  All the information provided on website is for educational purposes only.



This template was developed for its use in gophish (https://github.com/gophish/gophish - Gophish: Open-Source Phishing Toolkit), however can be used in any environment needed or desired)

The reason for its creation started because of limitations when gophish tries to import the website to create the email landing.

As gophish Documentation reads,

https://docs.getgophish.com/user-guide/documentation/templates

"A "Template" is the content of the emails that are sent to targets. They can be imported from an existing email, or created from scratch. They also support sending attachments.
Additionally, templates can contain tracking images so that gophish knows when the user opens the email."

Importing an Email
Gophish supports the ability to import an email from the raw content. To do this, click the "Import Email" button and paste in the original email content. This content is usually found through the "View Original" feature of many mail clients:


![](Images/original.png)


Google Meet Import email Issue on gophish:

When the original is copied and pasted inside the email exporter on gophish, the exported email looks like this

![](Images/Result.png)

We can see the exported email lacks pretty much all the google meet invitation design, for this reason ive created an html template to use on gophish using its own html editor.


