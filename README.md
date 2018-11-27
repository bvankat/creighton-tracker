# creighton-tracker
Tracking NCAA tournament odds for that blue team in Omaha. 

- Scrapes a few data sources for rankings and record projections. (Requests, Selenium, BeautifulSoup)
- Pulls them into an HTML table. (.getJSON())
- Calculates chance of making the tournament, assigns score based on each rating. (Educated guesswork)
- Averages the scores. (Math)
- Powers a needle gauge, a la #nytneedle from Election Night 2016. (Google Charts)
- Updates self automatically every 60 minutes. (crontab)

This repo is a fork of the OG Nebrasketball odds tracker at http://nebrasketball.info