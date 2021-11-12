# discord-presence
a custom discord presence app for your client

This app uses a discord client and their api to emulate a custom activity on your status.


## Get started with using this app

1. Head over to your discord developer portal and to the applications page over [here](https://discord.com/developers/applications).
2. Make a new application if you don't have one already, with any nice name that you like (this will be the name of your activity).
3. Go to the dashboard of your new application by clicking on it.
4. Go to the rich presence app and customize your app however you like.
5. Go the OAth2 section and copy the client ID.
6. Put the client ID in the presence app, and hit run! it should turn the "run" button to "stop" so you know it worked (should take about max 5 seconds to start).
7. Fill out the rest of the information from the dashboard as you like

# FAQ

> 1. **How do i get a custom image on my activity? What's this "Large/small image key"?**
* Well the large image key field takes in the "key" of the image that you get once you upload an image on the dashbboard, under Rich Presence > Art & Assets

> 2. **How do i get the timestamp working? I want it to show current time when i start it.**
* The timestamp fields take in a timestamp (number of seconds since epoch), which if you're not sure how to get, you can head over to [here](https://www.epochconverter.com). it lets you calculate timestamps. If you want the current time to show as start timestamp, use the keyword "now" instead, it automatically sets timestamp as the current time.
  
