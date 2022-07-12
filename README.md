# EmailModule
Quick and easy read and response, True/False returning, Check and Respond to Emails.

###### IMPORTANT FOR THIS TO WORK
> I recommend using an entirely new gmail account
1. go to [security](https://myaccount.google.com/u/2/security?hl=en)
2. Turn 2-step verification on.
3. go back to [security](https://myaccount.google.com/u/2/security?hl=en)
4. Scroll down to "Signing in to Google"
5. Click on App Passwords, select app as _other_. 
6. Name it.
7. After you click generate you will receive a new, 'app-specific' password.
8. After that place 'Email.py' into your project folder
9. in your import statements copypaste the following:

```
from Email import Email
```
9. in your code copypaste this and put in the correct user/password and it should work.
```
mail = Email("YourEmail@gmail.com", "NewPassword")
mail.sendMail("AnotherEmail@gmail.com", "hello", "this is a test")
```





`Look here for Initial Sources:` [Reading Emails with Python](https://www.thepythoncode.com/article/reading-emails-in-python) | 
[imaplib — IMAP4 protocol client](https://docs.python.org/3/library/imaplib.html) | 
[email — An email and MIME handling package](https://docs.python.org/3/library/email.html) | 
[webbrowser — Web-browser controller](https://docs.python.org/3/library/webbrowser.html)
