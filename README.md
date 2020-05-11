# Track my Music

## Inspiration
Finally, some free time for a pet project! Through this I want to combine two of my passions - learning and music.

## Background
I never hopped onto the Spotify bandwagon, even though I am an avid music listener and love to discover new stuff (with an almost academic fervor). There were essentially two factors - firstly, Spotify lacked entire albums and catalogues of the artists that I was tripping on (this was at least the case back in 2017-18 when I'd first checked them out). Secondly, I still enjoy the experience of browsing through a physical stack of records and CDs and listening to them while admiring the artwork in my hand.

However, the side effect of this offline model is that it lacks traceability. You can remember what you'd listened to for the last few days, but that's about it. Plus, there's so much more that I would like to know about my music playing habits - what records I haven't played for a while; what records did I play in sequence; what kind of music do I typically listen to at different times of the day and days of the week and so on.

This was essentially the inspiration for this project - tracking and drawing insights from the music that I play offline.

## The Product
Music Tracker (that's one boring name!) shall be a mobile app with a bunch of backend services that will do the following:
* Connect to my Discogs collection
* Track the songs and albums that I am playing, track if I played the full album, or just one side (for LPs)
* Track my turntable etiquettes - how long did I take to flip a record after the side ended (I have a manual turntable after all!)?
* Track the quality of my records - does it crack or pop (meaning the record needs cleaning)
* Track my mood throughout a day/week/month
* Recommend an album to play given a prediction of my mood or re-surfacing an album that I haven't played in a while or just something that is logically the next one

## The Technology
The other part of this project is to learn technologies that are new to me. Most of these have only risen to prominence since the last couple of years - essentially since the time I crossed over to the dark side (of engineering management) and haven't been coding on a daily basis.

Since, I don't expect to create a multi-billion dollar company with 100s of developers, I can take the liberty to be a bit wild and erratic (like, merge directly to master :exploding_head:). The intent is to just have fun without worrying about choosing a language or architecture that might become a nightmare to maintain or scale in the future, a.k.a., to hell with tech debts!

If time and patience permits, I would love to incorporate the following in this project:

### Must Have
* React Native with [Expo](https://expo.io/): No patience to learn Swift and Kotlin and can't do React Native from scratch. Have to use some kind of helper framework. Expo seems to be the popular one.
* GoLang: Loved the way I could read the whole language specs in just about 3 hours. Although I have written code in Go, but never developed something big and decent.
* ML: A buzz word that drives me nuts at times. But also something that I have barely scratched the surface of. Even though most ML algorithms are some form of Gradient Descent, I can't say I can choose and apply the right one given a problem - something to definitely get better at. Its application will be mostly around music feature detection, sentiment analysis, clustering and forecasting. Should be able to reuse stuff from the OSS ecosystem. We'll see if the training data becomes a bottleneck.

### Good to Have
* Rust: A language that I would sincerely like to explore, but have mostly shied away from. Curious to find out how a language scored so high on [developer happiness index](https://insights.stackoverflow.com/survey/2019) last year.
* Neural Nets: Deep learning to me seems more Voodoo magic than computer science. Maybe I can demystify it for myself if I get to try out a few during this journey.
