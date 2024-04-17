Forked from https://github.com/SealedSaucer/Online-Forever/blob/main/main.py

Discord Custom Status bot 24/7. Can be deployed on Render.

Getting token:
1. Open Discord on Browser, F12 or ctrl+shift+i. Go to Network tab. 
2. Click on some server or chat. Find 'Science' on the Network.
3. Find Authorzation. This is your `token`

Render side:
- Installation command: `pip install -r requirements.txt`
- Run command: `python main.py`
- Environment variables:
  - `token`: your_discord_token
  - `status`: normal status, can be `online`, `dnd`, `idle`
  - `custom_status`: status you want
