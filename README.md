# My Fake Season

[https://myfakeseason.netlify.app/](https://myfakeseason.netlify.app/)

I was digging around in some old project files and [found a screenshot](https://twitter.com/peruvianidol/status/1402809602224369666) of an old site I built, called My Fake Season, that made the front page of [kottke.org](https://kottke.org) back in 2005.

I built the site during the NBA lockout that year and used NBA Live 2005 to simulate the Chicago Bulls season. NBA Live 2005 had a feature where you could save a tab-delimited text file of the boxscore after each game, so I wrote some PHP scripts that let me upload those files along with a game recap and a screenshot to the site. From there, I was able to generate standings, player stats, league leaders -- pretty much everything you'd find on the NBA's website.

Unfortunately, while I still have the source code, the database that held all of the content was lost to time. Not to mention it's been at least 10 years since I even looked at PHP. Fortunately, the Internet Archive has [a cached version of the site](https://web.archive.org/web/20060104171900/http://www.myfakeseason.com/index.php) so I was inspired to recreate it using [Eleventy](https://11ty.dev) and modern HTML/CSS.

It's still a work in progress but I'll be working on it [live on Twitch](https://twitch.tv/peruvianidol) if you're interested in watching the process!
