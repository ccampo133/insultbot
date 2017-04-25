# insultbot

A Reddit bot to automatically insult in the style of Monty Python.

# Usage

    Usage: insultbot client_id client_secret username password target_username [user_agent]
        client_id:        your app's client ID (see: https://www.reddit.com/prefs/apps/)
        client_secret:    your app's client secret
        username:         the Reddit username of the account to which the app belongs
        password:         password to the aforementioned account
        user_agent:       the user agent of the bot (optional, default: <username>-insultbot)

Best run as a cron job, every few minutes or so.

# Requirements

 * Python 2.7+
 * [PRAW](https://praw.readthedocs.io/en/latest/)

