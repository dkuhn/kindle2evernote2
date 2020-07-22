# kindle2evernote2

Organize and Export Your Kindle's My Clippings.txt to Evernote.

## Get Started

### Dependencies

conda create 

### Evernote Developer Token

You'll need an Evernote Developer token. Go to [https://www.evernote.com/api/DeveloperToken.action](https://www.evernote.com/api/DeveloperToken.action) to get a developer token for you **production** account. Mine looks like: S=aDD:U=DDDDDD:E=15SDFSDFDF:C=35234234:A=en-devtoken:V=2:H=SDFKJSDKFJKSDJFKSDJFKJSD. Note that this is not the Evernote API secret.

Save the key in a text file. You will input this file's path as a required argument to Kindle2Evernote.py.

### Get Your Highlights

Access your Kindle Highlights via My Clippings.txt file in every Kindle, and save it locally.

The path to this local file is a required argument to Kindle2Evernote.py.

### Run the Script

Open a terminal window and run:

    python kindle2evernote.py `My Clippings.txt` en_auth.txt

If you wish to specify a specific notebook to add the highlights to, use the -n or --notebook option:

    python kindle2evernote.py `My Clippings.txt` en_auth.txt -n Books

To see log output, use the -v or --verbose option

    python kindle2evernote.py `My Clippings.txt` en_auth.txt -v

## About

This is a fork from of benhorvath@gmail.com [kindle2evernote2](https://github.com/benhorvath/kindle2evernote2) repo. This version is based on python3 and uses conda for installation.


