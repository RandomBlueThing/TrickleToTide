### Mobile tracking app for Trickle to Tide fundraising event 2020

https://www.justgiving.com/fundraising/Trickle-to-Tide

http://adventurelog.co.uk/ttt/


(@todo: Links for below)

- Xamarin Forms
- Xamarin Essentials 
- Shiny
- Azure
- GitHub Actions


### Android Setup

You'll need to add a secrets.xml file to Resources\values with the following content:

```
<?xml version="1.0" encoding="utf-8" ?>
<resources>
  <string name="api_key_google_maps">MAPS API KEY</string>
  <string name="api_key_ttt">TTT SERVICE API KEY</string>
  <string name="api_endpoint_ttt">TTT SERVICE ENDPOINT</string>
</resources>
```

![Deploy API](https://github.com/RandomBlueThing/TrickleToTide/workflows/Deploy%20API/badge.svg)
