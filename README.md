### ACT Framework Email Demo Applications

Usage:

To start in dev mode:

```bash
./run_dev
```

To start in prod mode:

```bash
./run_prod
```

Once started, go to `http://localhost:5460/` in your browser to view app UI. There you can find two text box for you to type in email address the email should be delivered. In case your email properties file are not updated with a valid SMTP server configuration, the app will mock email sent by print the emails in the console log.
