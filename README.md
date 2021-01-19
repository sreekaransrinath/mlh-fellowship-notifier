# mlh-fellowship-notifier

A small thing I made to notify you if you got an acceptance email from the fellowship. Plays the song 'You Suffer' by Napalm Death if you get an acceptance email.

First things first - Enable IMAP in your Gmail settings, so emails can be retreived using the IMAP protocol. [Link](https://mail.google.com/mail/u/0/#settings/fwdandpop)

Enable 2 Factor Authentication for your Google Account

Next, get yourself an app password to use here from google security settings - Head over to https://myaccount.google.com/security and select 'App Passwords'

Select Gmail from the drop down list, name it whatever you want, and copy the password it gives you.

Now cd into the repo folder, and run the script in your terminal as 
For Windows:
```
python main.py myemail@email.com myAppPassword
```
For Mac / Linux
```
python3 main.py myemail@email.com myAppPassword
```

Voila!

If you get an acceptance email from MLH, your PC will blast the song 'You Suffer' by Napalm Death at full volume.

Inspired by Bertram Gilfoyle from Silicon Valley - https://www.youtube.com/watch?v=gz7IPTf1uts

Feel free to DM me on [Twitter](https://twitter.com/sk4rn) if you have any questions. Feel free to contribute if you think you can improve this, any and all contributions welcome!