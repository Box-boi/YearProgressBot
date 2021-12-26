YearProgressBot
===============

YearProgressBot, a simple bot to update the percentage of year passed to give anxiety to all who look at it, written in Bash, for Telegram.

This Repo is highly inspired by [RedL0tus/YearProgressBot](https://github.com/RedL0tus/YearProgressBot), albeit it takes a completely different approach towards how the bot runs

Deployment
----------

1. Fork the reposistory:

2. Set The Following Github Actions Secrets:
```
GIT_TOKEN : Your GitHub Account Token, To Generate One Head Over To "Settings"-->"Developer-Settings"-->"Personal-Access-Tokens"
TG_TOKEN : Your Telegram Bot Token, To Get This, Head Over To Telegram And Start A Chat With @BotFather, Then Follow On-Screen Steps
GIT_EMAIL : Preferably Your Private GitHub Email, Get It From "Settings/Emails"-->Under The "Keep My Email Addresses Private". GIT_EMAIL Could also be your normal email.
GIT_USERNAME : Preferably Your GitHub Username, Although It Could Be Anything
```
2. Fill The Values In config.txt:
- Example Of CHAT_IDS: `CHAT_IDS="-1001642062053 -1001199512844 -1001387925474"`
- Example Of LENGTH: `LENGTH=20`

3. Make Sure Actions Are Enabled In GitHub:
- To Do This, Visit The "Actions" Tab Of Heroku
- If Done Right, Your Bot Should Begin Sending Year Percentage Messages Every 3 Days!

-------

Common Issues
----------

- You Haven't Added The Bot In Your Channel
- config.txt Isn't Populated With Incorrect Syntax
- Your Git-Token Expired. Make Sure To Make A Token Of Infinite Duration

-------

Features Nobody Asked For
----------

- Multiple Telegram Bots. For Some Unknown Reason, You Can Add Multiple Bot Tokens In The GitHub Secret Of `TG_TOKEN` And The Message Would Be Sent By All The Bots(As Long As They're In The Group(s)/Channel(s))
- The Syntax Follows: "$TOKEN1 $TOKEN2 $TOKEN3 ..."
Example: `TG_TOKEN` : `5070501422:AAFqmHTVuWQnEO7bhbvghubbbiufPIRX2-cY 7666262877:AaqILoveHentai7ygsgbbsyyAhsysvs-zY 5072701422:AAVuWQnILoveAnimeNiufPIRX2-cz`

-------

Why Does This Bot Exist?
----------

- This Bot/Script Exists With The Sole Purpose Of Reminding People(And Inducing Anxiety) Of The Passing Year. In A Futile Attempt Of Hoping That Another Year Doesn't Fly By Unnoticed

-------

## **Warnings :**
- This Bot/Script Uses GitHub Actions, Although Running One Lightweight Action Once In Three Days, Is In No Way Considered Abuse Of It. You Are Still Warned Of Account Suspension(If You Reduce The Cron-Job Frequency)(If You Already Have A Billion Other Consecutive GitHub Actions Running[Although GitHub Allows Only 20 Concurrent Jobs Per Account])

## **Credits :**
  * **RedL0tus** : [Github](https://github.com/RedL0tus/YearProgressBot)
