# XKCDalizer
XKCD indexer and search engine for CSCE 470 (Information Storage and Retrieval) 
William Flores, Nicholas Wong, Spencer Harder, Steven Tran

Uses tfidf cosine to evaluate queries and find the most relevant xkcd's.
Hosted on Heroku @ xkcdalizer.herokuapp.com

This is also the first implementation of a search API for xkcd (at least that I could find at the time).


### Usage
* Install the dependencies by using the command `npm install`
* To run the server use `npm start`
* To run the server in development mode (will automatically restart the server when files change) use `npm run devstart`

By default will run on port 3000

### Deployment
install the heroku command line tools and login with `heroku login` and the team credentials
To deploy use `git push heroku master`
