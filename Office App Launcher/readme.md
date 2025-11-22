# History of this app
I made this simple batchfile back in 2023, because I wanted to make it easier to open office apps on your computer. It's a very simple batchfile which can easily be modified. 

Feel free to add improvements!

# What operating systems does this work on?
- This will **only** work on Microsoft Windows.

# Outlook isn't working properly on the web section.
Outlook might not be working properly because of the differences between personal accounts and business accounts.

Replace this:
```
if %function.peposies.launch.web.option% == 1 start https://outlook.office.com
```

With:
```
if %function.peposies.launch.web.option% == 1 start https://outlook.live.com
```

# FAQ
- **Will this work on older versions of Microsoft Office, e.g., Office 2003?** This should work on older versions of Office, but some features in this app may not work, for example, OneNote will **not** run on versions of Microsoft Office older than 2003.

- **I don't want to use Microsoft Office, I want to use another office suite.** You can use other office suites, but you'll have to change the file path.

