# SpringBoot-freemaker-email-send
Send an Email using Spring boot and Apache Freemarker

<h4>Inspired by: https://memorynotfound.com/spring-mail-sending-email-freemarker-html-template-example/</h4>

This project allows you to send a cutomized email with attachments to a given email addres, subject, and content.

<h3>Customize Email Template</h3>

You can customize email template by editing "email.ftl" in project's "resources" folder.

<h3>How to Trigger an Email</h3>

- Edit "application.properties" file with your email address and password.<br>
<b>NOTE:</b> You have to enable accessing less secure app using:  https://myaccount.google.com/u/7/lesssecureapps?utm_source=google-account&utm_medium=web
- RUN the app
- Use provided postman script to trigger the request to the port which the app is running.<br>
  <b>NOTE:</b> You can edit its fields but the "from" field must contain the email address you are using to send the email. (the one you mentioned in the "application.properties")
