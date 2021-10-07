# 📧 Welcome Email 
A sample Ruby Cloud Function for sending a welcome email to a newly registered user.

## 📝 Environment Variables
Go to Settings tab of your Cloud Function. Add the following environment variables.

* **MAILGUN_API_KEY** -  API Key for Mailgun
* **MAILGUN_DOMAIN** - Domain Name from Mailgun


## 🎯 Trigger

When any user is created on the app, this function is automatically triggered. Allow events `account.create` and `users.create` from cloud function settings
