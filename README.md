**Coming from High Seas?** This project was inspired by [this post](https://hackclub.slack.com/archives/C07TSCMB4LC/p1735093405128619) in the Hack Club Slack.

# HC-Roadsign-Sticker

This is a web application which generates stickers similar to [this](https://cloud-20b5i3004-hack-club-bot.vercel.app/0image__1_.png) for an arbitrary coordinate.

**This project requires a [transit.land](https://www.transit.land) API key.** Sign up for an [Interline](https://app.interline.io/users/new) account and order a free Transitland API key.

## Usage

Click `Example` to see an example sticker, or:

1. Enter the latitude and longitude of a location, or click `Detect Location` to use your current location.
2. Add a destination name, and customize the colors if desired.
3. Select a transit line to display its vehicle type as an icon and the name and logo of its agency.
4. Click `Generate!` or press `Enter` to generate the sticker.

Click on the sticker to reload without regenerating (e.g. after changing the colors or destination name).

## Data Sources

The heading, route number, and distance are sourced from OpenStreetMap using the [Overpass QL API](https://wiki.openstreetmap.org/wiki/Overpass_API/Overpass_QL). Transit agency information is sourced from the [transit.land](https://www.transit.land) API.
