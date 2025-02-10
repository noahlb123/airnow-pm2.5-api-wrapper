# EPA AirNow API PM2.5 Wrapper
## Fill in time ranges on [noahlb123.github.io/airnow-pm2.5-api-wrapper](https://noahlb123.github.io/airnow-pm2.5-api-wrapper) to get hourly US PM2.5 data

### What is this?
* The EPA's [AirNow](https://docs.airnowapi.org/) "API" does not actually offer a programming interface, it is just a list of hyperlinked files, which makes large scale data collection difficult.
* This website is an API wrapper that semi-automates data collection from AirNow.

### How does it work?
* This website simply generates the download urls to each data file within a given time range, and then opens the urls in a new tab/window one at a time with user input.
Unfortunately, user input for each file is required.
I do not plan on maintaining this site, so it will break with small changes to AirNow's file structure, but all of its code is free and open source at [noahlb123.github.io/airnow-pm2.5-api-wrapper](https://noahlb123.github.io/airnow-pm2.5-api-wrapper)
