# Football-league
A single page application in angular js to fetch football competition's related data
## First screen (competition screen)
It uses competition api to fetch all the competitions
## second screen (league table)
It uses league table api to fetch list of teams for a competition
## Third screen (Players & fixture detail)
It uses player and fixture api to fetch player info of a team and 5 closest fixtures for that team along with the countdown timers 


## How to run this application
- As the application is calling ajax APIs, any browser will not allow `file` protocol to make these calls.
- To overcome this problem we need one web server like `apache` or `Nginx`.
- If you are running this code in `windows` put everything in `htdocs`.
- If you are running this in `unix` environment, put everything in `/var/www/` folder.
