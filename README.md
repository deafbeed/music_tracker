# Track my Music

## Inspiration
Finally, some free time to delve into a pet project! Through this project I want to combine two of my passions - learning and music.

## Background
Even though I am an avid music listener and love to discover new stuff (with an almost academic ferver), I never hopped onto the Spotify bangwagon. There were essentially two factors - Firstly, Spotify lacked entire albums and catalogues of the artists that I was tripping on (this was at least the case back in 2017-18 when I first checked them out). Secondly, I still enjoy the experience of browsing through a physical stack of records and CDs and picking up something that just about matched my mood at a given instance.

However, the side effect of this offline model is that it lacks trackability. You can probably remember what you had listened to for the last few days, but that's about it. Plus, there's so much more that I would like to know about my music playing habits - what records I haven't played for a while; what records did I play in sequence; what kind of music do I typically listen to at different times of the day and days of the week and so on.

This was essentially the inspiration for this project - tracking music that I play offline.

## The Product
Music Tracker (that's one boring name!) shall be a mobile app with a bunch of backend services that will do the following:
* Connect to my discogs collection
* Track the songs and albums that I am playing, track if I played the full album, or just one side (for LPs)
* Track my turntable etiquettes did I flip the record
* Track the quality of my records - does it crack or pop (meaning the record needs cleaning)
* Present a set of reports which not only tracks my music, but also my mood throughout a day/week
* Recommend playing something given a prediction of my mood, re-surfacing an album that I haven't played in a while or just something that is a logical next album to play

## The Technology
The other part of this project is to get my hands dirty with a bunch of new technologies. Most of these have only rose to prominence since the last couple of years - essentially since the time I crossed over to the dark side of engineering management and since the time I haven't been coding on a daily basis.

Since, I don't expect to create a multi-billion dollar company with 100s of developers around this idea, I can take the liberty to be a bit erratic and eccentric. The intent is to just have fun without worrying about choosing a wrong language or architecture that might become a nightmare to maintain or scale in the future, a.k.a., tech debts.

If time and patience permits, I would love to incorporate the following in this project:
### Must Have
* React Native with [Expo](https://expo.io/): No patience to learning Swift and Kotlin and can't do React Native from scratch. Have to use some kind of helper framework. Expo seems to be the de-facto here.
* GoLang: Loved the way I could read the whole language specs in about 3 hours. Although I have written some code in Go, but never developed something big and decent in it.
* ML: A _buzz word_ that drives me nuts at times. But also something that I've barely scratched the surface of. Although most ML algorithms are some form of Gradient Descent, I can't say I can choose and apply the right one given a problem - something to definitely get better at. Its application will be mostly around music detection, sentiment analysis, clustering and forecasting. Believe that I should get stuff in the OSS ecosystem for these.
### Good to Have
* Rust: A language that I would sincerely like to explore, but have mostly shyed away from. Curious to find out how a language scored so high on [developer happiness index](https://insights.stackoverflow.com/survey/2019) last year.
* Neural Nets: Deep learning to me seems more Voodoo magic than computer science. Maybe I can demistify it for myself if I can get to try out a few during this journey.
