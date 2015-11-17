# Twitter Real Time Analytics

#Twitter Statistics API

Realtime statistics on Twitter keywords

## Getting up and running

1. [Create a Twitter application](https://apps.twitter.com/)
2. [Create a free Pusher account](http://pusher.com/signup)
3. Fill the configuation options with the values from Pusher and Twitter
4. Add the keywords you want to track as an array of strings in `config.js`
5. Install the dependencies by running `npm install`
6. Test the API locally by running `node index.js` and [checking an API endpoint](http://localhost:3232/keywords.json)

#Twitter Statistics UI

1. [Set up the API](https://github.com/vipulkanade/Twitter-RealTime-Analytics/tree/master/tweeterStatisticsAPI) and make sure it's running
2. Install the server dependencies by running `npm install`
3. Install the front-end dependencies by running `bower install`
4. [Change the Pusher application key](https://github.com/vipulkanade/Twitter-RealTime-Analytics/blob/master/tweeterStatisticsUI/public/js/dashboard.js#L7) in `/public/js/dashboard.js`
5. [Change the API endpoint](https://github.com/vipulkanade/Twitter-RealTime-Analytics/blob/master/tweeterStatisticsUI/public/js/dashboard.js#L8) in `/public/js/dashboard.js`
6. Test the demo locally by running `node index.js` and [checking the graphs](http://localhost:3233)