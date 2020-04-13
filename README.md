# gbp-calendar-clean

A script to get rid of the remaining events stuck on your calendar!

### Usage

1. Create a virtual env (`virtualenv -p $(which python3)`)
1. Run `pip install -r requirements.txt` to install dependencies
1. Add an OAuth 2.0 token to this project's root folder (name it `credentials.json`)
1. Run `python clean.py`. it will print a list of deleted events


### How to get your OAuth 2.0 token

1. Go to console.developers.google.com/apis/credentials
1. Click `Credentials`
1. Click `+ Create Credentials`
1. Select `OAuth Client ID`
1. Click the Download button to get your token 