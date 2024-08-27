# Valorant Shop
Valorant Store Viewer with Multilingual Support (And Simple UI)

Translation API: https://github.com/ehd-wn/free-translate-api

RiotAuth API: Configure the https://github.com/floxay/python-riot-auth module as an API.
```python
url = "https://riotauth.vercel.app/auth/"
headers = {"username": username, "password": password}
response = requests.get(url, headers=headers)
auth_data = response.json()
```

# Web
`/store/USERNAME/PASSWORD/REGION/LANGUAGE/`: Shows the user's daily stores.

`/info/SKIN_UUID/LANGUAGE/`: Shows information about the skin of the offerid.

# In development
`/nightmarket/USERNAME/PASSWORD/REGION/LANGUAGE/`: Shows the user's Night Market.

`/bundle/USERNAME/PASSWORD/REGION/LANGUAGE/`: Shows the user's bundle information.

Wishlist (send notifications using Discord webhooks)

Other UI improvements
