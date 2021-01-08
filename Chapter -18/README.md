### Practice Questions:-


1. What is the protocol for sending email? For checking and receiving email?

**Answers**
```
SMTP and IMAP
```
2. What four smtplib functions/methods must you call to log in to an SMTP server?

**Answers**

``` smtplib.SMTP(), smtpObj.ehlo(), smptObj.starttls(), and smtpObj.login()```

3. What two imapclient functions/methods must you call to log in to an IMAP server?

**Answers**

```imapclient.IMAPClient() and imapObj.login()```

4. What kind of argument do you pass to imapObj.search()?

**Answers**
```
BEFORE, FROM and SEEN
```
5. What do you do if your code gets an error message that says got more than 10000 bytes?

**Answers**

```imaplib._MAXLINE = 10000000```

6. The imapclient module handles connecting to an IMAP server and finding emails. What is one module that handles reading the emails that imapclient collects?

**Answers**
```
pyzmail module
```
7. When using the Gmail API, what are the credentials.json and token.json files?

**Answers**
```
Credentials and tokens are for authentication of Google to use which account.
```
8. In the Gmail API, what’s the difference between “thread” and “message” objects?

**Answers**
```
single email is a message, whereas conversation of multiple emails is thread.
```
9. Using ezgmail.search(), how can you find emails that have file attachments?

**Answers**
```
pass has:attachment in the string to search()
```
10. What three pieces of information do you need from Twilio before you can send text messages?

**Answers**
```
SID number, authentication token number, and Twilio phone number.
```