# ideas
Some publicly shared app ideas

# apps

- [ ] Make https://templates.netlify.com/ dynamic and filterable.
   - Possibly under a [jamstack.page domain I have on sale](https://indiemaker.co/listings/jamstackpage) ([contact me](https://graficos.net/contact)).
   
- [x] [Static uptime robot](https://static-uptime-robot.netlify.com/):
   - Make use of lambda functions to fetch a configurable site from the cloud and respond if the site is "up and running". Uses a cron job to update its status. Currently reduced its frecuency to once per month due to build costs in the Netlify CD pipes. Left as a usage showcase of Netlify Functions + scheduled Github Actions. [Source](https://github.com/gangsthub/static-uptime-robot)
