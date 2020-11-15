# How to use

## Dependencies

```bash
pip install -r requirements.txt
```

## Add environment variables

`~/.bashrc` or `.env`
```
GMAIL_FNAME='nickname'
GMAIL_USER_ID='gmail id'
GMAIL_USER_PW='gmail password'
```

## Edit `run.py` and execute
```bash
python run.py
```

# Troubleshoot

```
smtplib.SMTPAuthenticationError: (535, b'5.7.8 Username and Password not accepted. Learn more at\n5.7.8  https://support.google.com/mail/?p=BadCredentials c12sm13961304pgi.14 - gsmtp')
```
> https://myaccount.google.com/lesssecureapps
> https://accounts.google.com/DisplayUnlockCaptcha