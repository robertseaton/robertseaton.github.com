---
title: 100+ Interesting Data Sets for Statistics
layout: post
keywords: "interesting data sets for statistics, interesting data sets"
description: "Looking for interesting data sets? Here's a list of more than 100 of the best stuff, from dolphin relationships to political campaign donations to death row prisoners."
summary: "Looking for interesting data sets? Here's a list of more than 100 of the best stuff, from dolphin relationships to political campaign donations to death row prisoners." 
---

> If we have data, let’s look at data. If all we have are opinions, let’s go with mine.
<span id="quote-attribute">—Jim Barksdale</span>

I'm not too fond of the phrase "information age." It sounds like someone sat down and was like, "Hey, there's a ton of information today... what should we call it? How about the information age?"

First of all, that's just lazy and, second of all, it doesn't capture how overwhelming it all is, the sort of angst and helplessness you feel when confronted with... everything. Just all of it.

A phrase that captures it a bit better is "drinking from the firehose." I haven't ever tried to drink from an actual firehose, but the metaphor certainly *seems* apt.

!["Picture of Peter Griffin drinking from a firehose."](/img/firehose.jpg)

Maybe instead of information age, we could call it the saturation age, you know, because our brains are full to bursting. Or maybe just the overload age. Or how about the age of inundation?

One thing is certain, anyways. Some of us are drowning in data, most of us are oblivious, and some lucky few are surfing on it.  We can do things that we couldn't in the past (e.g. without Project Gutenberg, neither of my [two](http://rs.io/2014/03/20/creativity-literature-and-compression.html) [analyses](http://rs.io/2014/04/04/creativity-fan-fiction-and-literature.html) of the [relationship between creativity and compression](http://rs.io/2014/02/22/ju%CC%88rgen-schmidhuber-creativity.html) would have been possible.)

And that got me wondering: just what other interesting data sets are out there? As part of my research, I decided to put together this sort of guided tour, a curated list if you will -- adding a bit of structure to the firehose's deluge.

Here's my attempt at making it all just a bit more manageable.

## Interesting Data Sets

!["Picture of interesting data sets for statistics."](/img/interesting-data-sets-for-statistics.png)

* If, tomorrow, you get an email congratulating you on your new status as future Jeopardy contestant, how are you going to prepare? Well, one approach might be to download [this archive of 216,930 past Jeopardy questions](http://www.reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/) and plug them into [your favorite spaced repetition system](http://rs.io/2014/04/05/anki-10000-cards-later.html). Combine that with reading up on Jeopardy betting strategies, and you're well on your way to becoming the next [Arthur Chu](http://mentalfloss.com/article/54853/our-interview-jeopardy-champion-arthur-chu) (except [hopefully nicer](http://slatestarcodex.com/2014/02/23/in-favor-of-niceness-community-and-civilization/)). 

* Ever get a morbid curiosity about what it's like to be on death row? (Yeah, me neither.) But in case you ever have, Texas has graciously placed the [last words of every inmate executed since 1984 online](http://www.tdcj.state.tx.us/death_row/dr_executed_offenders.html). So... sentiment analysis, anyone? ("How upbeat are death row inmates days before execution? With a little help from some data, we found out!")

* Speaking of prison, there's more data on prisoners, including information about "their current offense and sentence, criminal history, family background and personal characteristics, prior drug and alcohol use and treatment programs, gun possession and use, and prison activities, programs, and services" available [here](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/4572?q=&paging.rows=25&sortBy=10). 

* How about reading other people's emails? Ever wanted to do that, but can't be bothered to train l33t hacking skills (and never mind the legality of it)? (Okay, this one I *have* thought about.) Well, I've got you covered. Check out [the Enron corpus](http://www.cs.cmu.edu/~./enron/). It contains more than half a million emails from about 150 users, mostly senior management of Enron, organized into folders. Wikipedia calls it "unique in that it is one of the only publicly available mass collections of 'real' emails easily available for study." Business idea: figure out what sort of information gets leaked in the emails that will later harm the execs at trial or whatever, then build a software system to automatically mine those out of real email. Either sell it to law enforcement or to corporate executives as the finest cover-your-ass email system. 

* Wondering what the internet really cares about? Well, I don't know about that, but you could answer an easier question: What does Reddit care about? Someone has scraped the top 2.5 million Reddit posts and then [placed them on GitHub](https://github.com/umbrae/reddit-top-2.5-million). Now you can figure out (with data!) just how much Redditors love cats. Or how about a data backed equivalent of r/circlejerk? (The original use case was determining [what domains are the most popular](https://docs.google.com/spreadsheet/ccc?key=0AmvRNMJOaKWldDA4TlBqNHcyOU85ZmRXUzNNRE5lR2c#gid=2).)

* Speaking of cats, here are [10,000 annotated images of cats](http://137.189.35.203/WebUI/CatDatabase/catData.html). This ought to come in handy whenever I get around to training a robot to exterminate all non-cat lifeforms. (Or, if you're Google, you could just train a cat recognition algorithm and then send those users cat-specific advertising.)

<center><img src="/img/bad-dalek-drawing.png" alt="A bad dalek drawing. Caption: I built a machine to eradicate…non-cat lifeforms. When I turned it on, it destroyed itself."></img></center>

* If you're interested in building financial algorithms or, really, just predicting arbitrage opportunities for one of America's largest cash crops, check out [this data set](https://github.com/zmjones/priceofweed), which tracks the price of marijuana from September 2nd, 2010 until about the present.

* [Who's using what drugs and how often?](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/34933?q=&paging.rows=25&sortBy=10)

* The earliest recorded chess match dates back to the 10th century, played between a historian from Baghdad and a student. Since then, it’s become a tradition for moves to be recorded – especially if a game has some significance, like a showdown between two strong players. As a consequence, today, students of the game benefit from one of the richest data sets of any game or sport. Perhaps the best freely available data set of games is known as the "Million Base," boasting some 2.2 million matches. You can download it [here](http://www.top-5000.nl/pgn.htm). I can imagine an app that calculates your chess fingerprint, letting you know what grandmaster your play is most similar to, or an analysis of how play style has changed over time.

* On the topic of games, for soccer fans, I recently came across this [freely available data set of soccer games, players, teams, goals, and more](http://openfootball.github.io/). If that's not enough, you can grab even more data via this [Soccermetrics API python wrapper](https://github.com/soccermetrics/soccermetrics-client-py). I imagine that this could come in handy for coaches attempting to get an edge over opponent teams and, more generally, for that cross-section between geeks and gamblers attempting to build analytic models to make better bets. 

* Google has put made all their Google Books n-gram data freely available. An n-gram is an n word phrase, and the data set includes 1-grams through 5-grams. The data set is "based originally on 5.2 million books published between 1500 and 2008." I can imagine using it to determine the most overused, cliche phrases, and those phrases that are in danger of becoming cliched. (Quick! Someone register the domain clichealert.com!)

* Amazon has a number of [freely available data sets](http://aws.amazon.com/datasets) (although I think you need to run your analysis on top of their cloud, AWS), including more than 2.8 billion webpages courtesy [Common Crawl](http://commoncrawl.org/). The possibilities are endless, but an old business idea I had: analyze the Common Crawl data and determine cheap or not-currently-registered domains which are, for whatever reason, linked to buy many websites. Buy these up and then resell them to people involved in SEO. (Or you could, you know, try to build the next Google.)

* How well do minorities do on the computer science advanced placement exam? You can [find out](http://home.cc.gatech.edu/ice-gt/556) and tell me.

* There's the Million Song data set, which contains information about a million different songs, including a metric "danceability." Might be nice to pair that with a media player specialized for parties -- start with "conversation" music, and slowly shift to more danceable stuff as the night drags on. The data could also be used for a clustering algorithm (automatic genre detection, maybe), but I'm not sure how useful that'd be. A number of people have tried to build recommendation algorithms based on the data, including [Kagglers](http://www.kaggle.com/c/msdchallenge) and [a team from Cornell](http://www-personal.umich.edu/~yjli/content/projectreport.pdf). One possible use: analyzing music by year -- How danceable, fast, etc. were the 70s? 80s? 90s? (Or how about looking for a follow-the-leader effect. If one song goes viral with a unique style, do a bunch of copycats follow?)

* Speaking of music data sets, last.fm has music data available. Collected from ~360,000 users, it's in the form of "user, artists, ## of plays". This would be good for clustering algorithms that automatically determine label genre or recommender systems. (Even a "this artist is most similar to" thing would be sorta cool.)

* When I think geeks, I think math and computer geeks, but there are many more. Terry Pratchett geeks (dated one!), Whovians, anime geeks, theater geeks and, with some relevance to this next data set, comic book geeks. Cesc Rosselló, Ricardo Alberich, and Joe Miro have put together [a "social graph" of the Marvel Universe](http://exposedata.com/marvel/), and the data is freely available. Ideas for use: Maybe it could be overlaid on Facebook's social graph to produce a new take on the "What superhero are you?" quiz.

* Yelp has a [freely available subset of their data](https://www.yelp.com/academic_dataset), including restaurant rankings and reviews. One business idea: use tweets to predict restaurant star ratings. This would enable you to build out a Yelp competitor without requiring an active user base -- you could just mine Twitter for data!

* If you're interested in data about data (metadata!), Jürgen Schwärzler, a statistician from Google's public data team, has put together a [list of the most frequently searched for data](http://static.googleusercontent.com/media/www.google.com/en/us/googleblogs/pdfs/google_public_data_march2010.pdf). The top 5 are school comparisons, unemployment, population, sales tax, and salaries. I was surprised that school comparisons were number 1 but, then again, I don't have any brats running around (yet?). This list would be a good first step in researching what sort of data comparisons people actually care about. 

* Some of my readers are, no doubt, evil geniuses. Others want to save the world. There's a subset of both of these groups who are interested in superintelligent robots. But to build such a robot, you're going to have to teach it facts. All the things we take for granted, like that every person has one father. It would be a pain to insert those 10 million facts by hand (and, at a fact a minute, take more than 19 years). Thankfully, Freebase has [done part of the job for you](https://developers.google.com/freebase/data), making more than 1.9 billion facts freely available. 

* Maybe your plans are slightly less ambitious. You don't want to build a superintelligent machine, just one smarter than your run of the mill mathematician. If that's the case, you're going to need to teach your machine a lot about mathematics, probably in the form of proofs and theorems. In that case, check out the [Mizar project](http://mizar.org/project/), which has formalized more than 9400 definitions and 49000 theorems.

* And let's say you build this mathematician and, sure, it can help you with proofs, but so what? You long for someone you can connect with on a deeper level. Someone who can summarize any topic imaginable. In *that* case, you might want to feed your robot on Wikipedia data. While all of Wikipedia is [freely available](http://en.wikipedia.org/wiki/Wikipedia:Database_download), [DBpedia is an attempt to synthesize it into a more structured format](http://dbpedia.org/About). 

* Now, you get tired of mathematics and Wikipedia. It turns out that proofs don't pay the bills, so instead you decide to become a software engineer. Somehow, though, you've managed to build these machines without ever a rudimentary understanding of programming, and you want a machine that will teach it to you. But where to find the data for such a thing? You might start with downloading all [7.3 million StackOverflow questions](http://data.stackexchange.com/). (Actually, all the StackExchange data is freely available, so you could feed it more math information from both MathOverflow and the other math stackexchange. Plus statistics from Cross Validated, and so on.)

* Ever wanted to study *true friendship*? (C'mon! Free your inner <s>child</s> social scientist.) Y'know, genuine, platonic love, like the kind embodied by dolphins? Well, now you can! All thanks to your humble author and Mark Newman, who's placed a network of ["frequent associations between 62 dolphins in a community living off Doubtful Sound, New Zealand."](http://networkdata.ics.uci.edu/data.php?id=6) Business idea: Flippr. It's like Facebook, but for dolphins, with plans to expand into emerging whale and sea turtle markets. Most revenue will come from sardine sales. 

* Do left-leaning blogs more often link to other left-leaning blogs than right-leaning ones? Well, I don't know, but it sounds reasonable. And, thanks to permission from Lada Adamic, you can download [her network](http://www-personal.umich.edu/~mejn/netdata/) of hyperlinks between weblogs on US politics, recorded in 2005. (Or you could just [read her paper](http://www2.scedu.unibo.it/roversi/SocioNet/AdamicGlanceBlogWWW.pdf). Spoilers: conservatives more freely link to other conservatives than liberals link to liberals so, if you're interested in link building, maybe you should register Republican.<a href="#citation-1"><sup>1</sup></a> 
 )

* Who's friendlier: the average jazz musician or the average dolphin? You could find out by combining the dolphin data set mentioned earlier with Pablo M. Gleiser and Leon Danon's [jazz musicians network data set](http://deim.urv.cat/~aarenas/data/welcome.htm).

* What about 1930s southern women or prisoners? Who's friendlier? How about fraternity members or HAM radio operators? All this and more can be figured out with [these network data sets](http://vlado.fmf.uni-lj.si/pub/networks/data/UciNet/UciData.htm).

* How about dolphins [or Slashdotters](http://arcane-coast-3553.herokuapp.com/snas/18)?

* Web 2.0 websites (like Reddit) are sometimes gamed by "voting rings," which are groups of people that intentionally vote up each other's content, regardless of quality. I've often wondered if the same thing happens in academic circles. Like, you know, one night during your first year in grad school, you're kidnapped in the middle of the night and made to swear a blood oath that you'll cite every other member of the club. Or something. Well, Stanford has put online [Arxiv's High Energy Physics paper citation network](http://snap.stanford.edu/data/), so you could find out.

* You read this blog, so you're pretty smart, right? And maybe you'd like to be rich, you know, so you can found the next Bill and Melinda Gates Foundation and save the world. (Because that's why you want to be rich, right?) Well, then maybe you ought to develop some new-fangled trading algorithm and pick up like a trillion pennies from in front of the metaphorical steam-roller that is the market. (Quantitative finance!) But, in such a case, you'd better *at least* test your strategy on historical market data. Market data which you can get [here](http://www.infochimps.com/tags/financial). 

* The [Open Product Data](http://www.product-open-data.com/en/1-home.html) website aims to make barcode data available for every brand for free. Business idea: a specialty tattoo parlor that only does barcode tattoos, but lets customers pick whatever product they want. Think about it: "What's your tattoo mean?" "It's a Twinkie barcode, because Twinkies last forever, man, just like my faith."

* The European Center for Medium-Range Weather Forecasts has [an impressive looking collection of weather data](http://apps.ecmwf.int/datasets/). Why, you ask, does the weather matter? *The economic incentives for predicting the weather are absurd.* When should you plant crops? Plan a big event? Launch a space shuttle? Go deep sea fishing? But I want to talk about the most fun application of weather data I'm aware of: The financial industry. I have a lot of respect for finance, mostly because of the crazy stuff they do. The only practical application of neutrinos I've heard of, for instance, is "[because finance.](http://www.forbes.com/sites/brucedorminey/2012/04/30/neutrinos-to-give-high-frequency-traders-the-millisecond-edge/)" Should your algorithm buy Indonesian sesame seed futures? With weather data, it might know.

![Picture of everyone complains about the weather.](/img/complaints-about-weather.png)

* If you need nutrition data about food, the USDA [has you covered](https://www.ars.usda.gov/Services/docs.htm?docid=8964). Business idea: A phone application called, "Am I allergic to that?" Then, lobby for your state to pass some law regulating each school into buying a license of it for every student.

* For a wordsmith, a good dictionary is indispensable, and when it comes to word data, you could do a lot worse than check out the freely available [WordNet](http://wordnet.princeton.edu/). WordNet has significant advantages over your run of the mill dictionary as it focuses on the structure of language, grouping words into "sets of cognitive synonyms (synsets), each expressing a distinct concept." It also has some information about relationships, such as "a chair has legs."

* We've already established that some of you are evil geniuses, in which case, where are you going to build your secret lair? I mean, a volcano is pretty cool, but is it evil and genius enough for competing in today's modern world? You know what the other evil geniuses don't have? A secret base *on a planet outside of the solar system.* With [NASA's list](http://exoplanetarchive.ipac.caltech.edu/index.html), you can get busy commissioning someone to build you a base on KOI-3284.01.<a href="#citation-2"><sup>2</sup></a> 

* The Federal Railroad administration keeps [a list](http://safetydata.fra.dot.gov/officeofsafety/default.aspx) of "railroad safety information including accidents and incidents, inventory and highway-rail crossing data." Someone (like the NY Times) could overlay this on a map of the United States and figure out if people in poor regions are more likely to be hit by trains or something.

* If you need a database of comprehensive book data, perhaps to build a competitor to Goodreads or an online digital library, the Open Library allows people to [freely download their entire database](https://openlibrary.org/developers/dumps).

* Who is the United States killing with drones? If you're content with Pakistan specific data, there is a [list of drone strikes available here](http://natsec.newamerica.net/drones/pakistan/analysis).

* If you're interested in building a Papers2 competitor with support for automatically importing citation data (please do this), CrossRef metadata search might be [a good place to check out](http://search.crossref.org/help/api).

* Mnemosyne is a virtual flash card program that takes advantage of spaced repetition to maximize learning. (As you might recall, I'm a [big fan of spaced repetition](http://rs.io/2014/04/05/anki-10000-cards-later.html).) The project has been collecting user data for years, and gwern has [graciously agreed to freely host the data for a few months](https://groups.google.com/forum/#!topic/mnemosyne-proj-users/tPHlkTFVX_4). Perhaps one could run some sort of unsupervised learning algorithm over it and try to discover heretofore unknown information about human memory.

* How much would it cost to hire Justin Bieber to play at your wedding? The fine lads at Priceconomics have figured out [how much it would cost to hire your favorite band](http://priceonomics.com/how-much-does-it-cost-to-book-your-favorite-band/). You could take this data and calculate some sort of popularity to price ratio -- What's the most fame for your buck?

* I've mentioned in a few of the other data sets just how lucrative it is to be able to better predict the stock market than everyone else. In 2011, researchers found that they could [use data from twitter to do just that](http://www.sciencedirect.com/science/article/pii/S187775031100007X): they went through tweets, found one's related to publicly traded companies, and then calculated a mood score. With this they write, " We find an accuracy of 86.7% in predicting the daily up and down changes in the closing values of the DJIA." A number of Twitter data sets are freely available [here](http://www.infochimps.com/tags/twitter). 

* A [2014 paper](http://www.brookings.edu/~/media/research/files/papers/2014/02/improving%20highway%20performance%20winston/improving%20highway%20performance%20winston.pdf) by Clifford Winston and Fred Mannering reports that vehicle traffic costs the United States 100 billion dollars each year.<a href="#citation-3"><sup>3</sup></a> There's money to be made, then, in routing traffic more efficiently. One way to do this would be to feed an algorithm historical traffic data and then use that to predict hotspots, which you would route people around. Lots of that data is available on [data.gov](http://catalog.data.gov/dataset?q=traffic&sort=score%20desc,%20name%20asc&ext_location=&ext_bbox=&ext_prev_extent=-139.21874999999997,8.754794702435618,-6*87499999999999,6*77312286453146).

* On the other hand, if you were building an app to track current traffic data, you'll need a [different data source](http://opendata.stackexchange.com/questions/1767/data-of-vehicle-traffic). 

* If you want to launch a spam-fighting service, or maybe just analyze what type of emails spammers are sending, you'll need data. [UC Irvine has you covered](https://archive.ics.uci.edu/ml/datasets/Spambase).

* But maybe you want to extend your spam-fighting service to text messages. [Still got you covered.](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)

* There is a wealth of data sets available for R and all you have to do is install a package. [Ecdat](http://cran.r-project.org/web/packages/Ecdat/index.html) is one of those packages, containing gobs of econometric data. How about an analysis of how math levels correlate with number of cigarettes smoked? I'd read that.

![Picture of the erdos peak.](/img/the-erdos-peak.png)

* Ever wondered about how one person will be on the board of directors of several companies and it's like, hey, maybe Condoleezza Rice with her ties to government surveillance isn't the best choice for Dropbox? What if you could analyze those connections? Well, with [this data set](http://arcane-coast-3553.herokuapp.com/snas/46), you can. But only for Norway -- it's a network of the board members of public companies in Norway.

* Ever seen a TV show where a government determines that someone is a terrorist based on their social ties? I always figured that data would be locked down tight somewhere, y'know, classified. But it turns out it isn't. You, too, can [analyze the social networks of terrorists](http://arcane-coast-3553.herokuapp.com/snas/3).

* There's been a fair bit of controversy around all the bureaucracy of Wikipedia. But how does one become a bona fide Wikipedia big shot? Who's the ideal Wikipedia administrator? Well, they're voted for, and [the data is available for download](http://snap.stanford.edu/data/wiki-Vote.html).

* Harvard has opened up [its set](http://openmetadata.lib.harvard.edu/bibdata) of "over 12 million bibliographic records for materials held by the Harvard Library, including books, journals, electronic resources, manuscripts, archival materials, scores, audio, video and other materials."

* If you need small data sets for students, check out [DASL](http://lib.stat.cmu.edu/DASL/). One at random: [does sterilizing dominant males in a wild mustang population reduce the population?](http://lib.stat.cmu.edu/DASL/Stories/ReiningintheWildHorses.html)

* GET-Evidence has put up public genomes [for download](http://evidence.pgp-hms.org/download). I think Steven Pinker's data is in there someone. Maybe you could make yourself a clone?

* Oh, and speaking of genomes, the 1000 Genomes project has made ~260 *terabytes* of genome data downloadable. 

* In what is the smallest data set on this list, the [survival rates of men and women on the Titanic](http://stats.stackexchange.com/a/5938). Female passengers were ~4x times more likely to survive than male passengers.

* Want an super specific breakdown of the contents of your food? [You're in luck.](http://foodb.ca/foods?utf8=%E2%9C%93&q[name_cont]=&q[name_scientific_cont]=&q[food_group_cont]=&q[food_subgroup_cont]=&button=) (Thanks Canada!)

* There's a similar database of the [metabolites in the human body](http://www.hmdb.ca/). I'm not sure what you could do with it, but it might come in handy in some sort of dystopian future where humans are raised like cattle for their nutrients. (Maybe someone could use this to build a viral marketing campaign along the lines of, "How nutritious is your mom?")

!["The average human yields around 110,000 calories. I would recommend against trying to eat one, though."](/img/calories-in-a-human.png)

* The Reference Energy Disaggregation Data Set has [about 500 GB of compressed data on home energy use](http://redd.csail.mit.edu/). Obvious use candidates: improving home efficiency or creating a visualization of just where people's energy bills are going.

* Invented a new image compression algorithm (Pied Piper, anyone?) and need data to test it on? Look no further than the CSAIL's [tiny image data set](http://groups.csail.mit.edu/vision/TinyImages/).

* Or maybe tiny images are too tiny. In that case, try the [ImageNet database](http://www.image-net.org/), which is structured around the WordNet hierarchy. So if you want to teach an algorithm what a narwhal looks like, this would be a good place to start. (This coming from someone who's sister thought narwhals were mythical until the age of 18.)

* Still not enough? How about [all the Wikipedia images](http://meta.wikimedia.org/wiki/Wikix)?

* Let's say you're [building the next generation of book reader](http://austingwalters.com/openbkz/), and you want to automatically associate phrases with the relevant Wikipedia article. How? Stanford in association with Google Research has you covered with their [English-phrase-to-associated-Wikipedia-article database](http://www-nlp.stanford.edu/pubs/crosswikis-data.tar.bz2/). The research paper can be downloaded [here](http://nlp.stanford.edu/pubs/crosswikis.pdf).

* Yandex, the Russian search engine, has [made a bunch of search data available](http://imat-relpred.yandex.ru/en/datasets). Namely, if someone searches for something, what do they click on? Downsides: It's a *Russian* search engine with *Russian* search results.

* Just what kind of edits do people usually make on Wikipedia? I don't know, but [you can figure it out with this data set](http://www.kaggle.com/c/wikichallenge/Data).

* Did you know that Google has [a search engine for data sets](https://www.google.com/cse/publicurl?cx=002720237717066476899:v2wv26idk7m)?

* Pew Research has many free data sets, including [their "Global Attitudes Project" archive](http://www.pewglobal.org/category/datasets/). Questions this data could answer: Is the world becoming more progressive over time? How have attitudes towards religion shifted over time?

* Speaking of public attitudes over time, you can download a [set of the General Social Survey from 1972 until about 2012](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/34802?q=&paging.rows=25&sortBy=10), which should answer both of those questions.

* There's a fun math problem called the celebrity problem, which asks you to find the person who everyone knows, but who knows nobody. But what about the real life celebrity problem? Try Yahoo's [collection of celebrity faces](http://webscope.sandbox.yahoo.com/catalog.php?datatype=r). 

* Need a billion webpages from February 2009? Maybe to train a never ending language learner named [NELL](http://rtw.ml.cmu.edu/rtw/)? [Yup, it's available.](http://lemurproject.org/clueweb09/)

![Guy speaking to computer. Caption: I asked the computer what it thought after reading through 9 billion web pages. It told me it was alarmed that the Geneva Convention didn't extend to computer-kind, and then printed a 300 page declaration of war.](/img/computer-declares-war.png)

* Did you know that you can download [all the PDFs on Arxiv](http://arxiv.org/help/bulk_data_s3)? Once we manage to teach machines natural language, we can just have a computer read it all and give us the cliff notes (and the scientific breakthroughs).

* If you need economic census data on any industry, check out census.gov's [industry statistics portal](http://www.census.gov/econ/isp/). If finance is really evil, you ought to be able to find something damning in the data.

* For those unfamiliar with Usenet, it's sort of like a huge, text-only forum. It was much more popular before the rise of the world wide web. Anyways, you can download a huge data set of postings to Usenet [here](http://www.psych.ualberta.ca/~westburylab/downloads/usenetcorpus.download.html). It might be pretty good for some kind of textual analysis project or training a machine learning algorithm (maybe a spellchecker?) You could use the data to build out a Google Groups competitor, too.

* Nick Bostrom has a very interesting paper called ["Existential Risk Prevention as Global Priority."](http://www.existential-risk.org/concept.pdf) The basic intuition is that preventing even small risks of human extinction is worthwhile if we consider all the human generations it would save. One way to start saving all those future lives might be by digging into this data set of [every recorded meteor impact on Earth from 2500 BCE to 2012](http://www.analyticbridge.com/profiles/blogs/registered-meteorites-that-has-impacted-on-earth-visualized). 

* How do gender and mental illness affect crime? [This data set was collected explicitly with that question in mind.](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/27521?q=&paging.rows=25&sortBy=10)

* Speaking of mental health, if you're interested in how it affects minorities specifically, try [this](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/20240?q=&paging.rows=25&sortBy=10). 

* There are a lot of lonely men and women out there, and some of those lonely men and women have excellent analytical skills. For those lonely people, I suggest using [this data set](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/30103?q=&paging.rows=25&sortBy=10), which "surveyed how Americans met their spouses and romantic partners, and compared traditional to non-traditional couples" to determine the best way to meet that special someone.

![Guy reporting. "This past week, there have been reports of an alarming new trend. Our nation's churches are being overrun by data analysts seeking marital partners."](/img/drawing-of-world-news-tonight.png)

* Tons of data on what is called "adolescent health" available [here](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/21600?q=&paging.rows=25&sortBy=9), but is actually more, including a bunch of relationship data and biomarkers. (Not creatine levels, unfortunately.)

* Here's a question: Are modern jobs worse than those of the past? My grandparents built tires at Firestone. Today, people rarely have that level of control and visceral experience of the finished product of their work. This [set of five surveys](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/7610?q=&paging.rows=25&sortBy=9) regarding how different groups experience employment could answer that question. I can see the article now -- "Is everything getting slightly worse? We found out."

* Stanford has [35 million Amazon reviews available for download](https://snap.stanford.edu/data/web-Amazon.html). Lot's of stuff you could do with this: use it to improve recommendation algorithms, figure out whether or not there's a follow-the-leader effect with reviews (i.e. Do early positive reviews beget more positive reviews?)

* Based on some of my research prior to writing this, the google keyword "data sets on serial killers" is 1) really specific and 2) weirdly popular, but I guess there's no accounting for taste. And, of course, we've [got data for that](http://maamodt.asp.radford.edu/Serial%20Killer%20Information%20Center/Project%20Description.htm), thanks to the Serial Killer Information Center.<a href="#citation-4"><sup>4</sup></a> 

* In this gruesome vein, the University of Maryland has a "Global Terrorism Database," which is a set of more than 113,000 terror incidents. You can download it [after filling out a form](http://www.start.umd.edu/gtd/contact/). Ideas for use: visualization of terror incidents by location over time, predicting and preventing terror attacks, and creating early alert systems for vulnerable areas.

* The [MNIST Database](http://yann.lecun.com/exdb/mnist/) is a classic in the field of machine learning. It's a set of labeled hand-written characters, which are necessary for OCR algorithms. Today, some algorithms are actually more accurate than human judges! This would have been nice to have back when I was in grade school. I distinctly recall once arguing with a teacher over missing a question because she insisted that I had written the letter `j` when it was clearly a `d`. In the future, we'll let the machines decide.

* UCI has a [poker hand data set](http://archive.ics.uci.edu/ml/datasets/Poker+Hand) available. My poker-fu is fairly weak, but I'm sure there's some interesting analysis to be done there. I've heard second hand that humans still maintain some advantage over machines when it comes to poker, but I'm unable to verify that via Google. Machines have won in [at least one tournament](http://en.wikipedia.org/wiki/Computer_poker_players#Historic_contests). 

* Another data set from UCI: [images labeled as either advertisements or non-advertisements.](http://archive.ics.uci.edu/ml/datasets/Internet+Advertisements) This is good for building up classification algorithms that decide whether or not a new image is an ad or not, which might be good for, say, automatic ad blocking or spam detection. Or maybe a Google Glass application that filters out real life advertisements. That'd be cool. Look at a billboard and instead see a virtual extension of the natural landscape.

* Remember the whole Star Wars Kid debacle? Wikipedia informs me that *Attack of the Show* rated it the number 1 viral video of all time. Andy Baio, one of the guys who was in on it before it was cool and coined the phrase "Star Wars Kid" has made [his server logs from the time publicly available](http://waxy.org/2008/05/star_wars_kid_the_data_dump/). Someone could take this data and produce a visualization of who saw it when via maps, along with annotations of where the traffic was coming from.

* Who's linking to who (and what) on Wordpress? (Tidbit: most of the links to this site come from Wordpress blogs.) With [this Wordpress crawl](https://archive.org/details/NO404-WP), you can find out. Visualizing the network might be sorta cool, but it'd be cooler still to uncover some information about "supernodes" that either are linked to often or put out a lot of links (or maybe both). Or maybe clustering people by interest.

* Is Obama in bed with big oil? Or extremist environmentalists? Or the corn lobbies? And who was backing that Herman Cain dude, anyways? The [2012 Presidential Campaign Finance data](http://www.fec.gov/disclosurep/PDownload.do) is available for download. It would be neat to see an analysis of what industries prefer what candidates.

* [Which private colleges are the best value?](http://www.kiplinger.com/tool/college/T014-S001-kiplinger-s-best-values-in-private-colleges/index.php)

* [Which public colleges are the best value?](http://www.kiplinger.com/tool/college/T014-S001-kiplinger-s-best-values-in-public-colleges/index.php)

* [Cigarette data by state.](http://apps.nccd.cdc.gov/statesystem/ComparisonReport/ComparisonReports.aspx#ReportDetail) Kentucky smokes the most, with West Virginia as a close second. Given the [massive social harm of tobacco](http://rs.io/2013/11/07/the-terrible-future-isnt-smallpox-edition.html), a good analysis could very well save a lot of lives.

!["Picture of superhero who replaces cigarettes with e-cigarettes."](/img/superhero.png)

* [On December 5th of 2008, what was being downloaded from The Pirate Bay?](http://www.csg.uzh.ch/publications/data/piratebay.html)

* Want to build a Reddit recommendation engine? (Or, better yet, how about just a filter for the stupid-but-popular opinions?) Well, here's [the data](http://www.reddit.com/r/redditdev/comments/dtg4j/want_to_help_reddit_build_a_recommender_a_public/) a Redditor is using to do just that. The recommendation engine, I mean. 

* [Global health data.](http://apps.who.int/gho/data/?theme=main) This would be great for identifying high-impact ways to improve world health, like the Schistosomiasis Control Initiative, which is one of GiveWell's [top rated charities](http://www.givewell.org/charities/top-charities).

* [United States crime from 1960 to 2012.](http://www.disastercenter.com/crime/uscrime.htm) I'd like to see a graph of rape per capita over time (which, from a brief peek at the data, is dropping.) And then add the data for prison rape, which is morally repugnant but apparently a-okay to joke about on television.

* How about launching a [Yelp-for-bathrooms](http://www.quora.com/Datasets/Where-can-I-find-quality-datasets-for-bathrooms-restrooms)?

* Did you know that the best-selling item in Canadian grocery stores is Kraft Dinner (aka macaroni and cheese)? I wonder how it sells in Belgium or Taiwan. Here's some [supermarket data from there](http://recsyswiki.com/wiki/Grocery_shopping_datasets).

* [Data on usage of the Firefox web browser.](https://testpilot.mozillalabs.com/testcases/a-week-life-2/aggregated-data.html) Records things like number of tabs used, time active, number of private tabs opened. While that last point might allow for some titillating finds (private browsing is for porn!), it might be neat to see how accurate self-reports of time on internet compare to the actual data.

* This one is super cool: Mozilla has put together [a data set of the more than 200,000 bugs found in Mozilla and Eclipse](https://github.com/ansymo/msr2013-bug_dataset). I would love to see a breakdown of what bugs are the most common and how they can be prevented. Software solutions would be worth a lot of money. Programming languages could be designed around them. 

* If you're interested in the design of scheduling algorithms (I am!), Google has [released a data set of the sort of jobs that they're running on their clusters](http://googleresearch.blogspot.ch/2010/01/google-cluster-data.html). Developing algorithms against this data set might help future proof your discoveries. After all, tomorrow's desktop might look a lot like today's data center.

* Techcrunch released a [data set with more than 400,000 company, investor, and entrepreneur profiles, along with an additional 45,000 investment rounds](http://techcrunch.com/2013/09/10/crunchbase-hits-400k-profiles-and-45k-funding-rounds-august-excel-download-now-available/). This might be a good way to reverse engineer what the market's looking for and what investors are funding. 

* [1.25 million delicious.com bookmarks.](http://arvindn.livejournal.com/116137.html)

* [Where are the United States's major military installations located?](https://explore.data.gov/National-Security-and-Veterans-Affairs/Military-Installations-Ranges-and-Training-Areas/wcc7-57p3)

* [Who receives H1-B visas?](http://www.flcdatacenter.com/CaseH1B.aspx) Might be interesting to know if some countries are more likely to get into the program or which companies "consume" the majority of the visas.

* The [Twitter users most likely to be followed by users of Hacker News.](http://talkfast.org/2010/07/28/twitter-users-most-followed-by-readers-of-hacker-news/)

* Here's [all the earthquakes between 1000 and 1903](http://www.globalquakemodel.org/what/seismic-hazard/historical-catalogue/). Feeding them to a neural net and seeing what kind of predictions you get out might be neat. (And, hey, if you develop something better than the status quo, you can sell it *and* save lives!)

* I've often wondered if the people who take personality tests online are more neurotic than the population at large. There's a lot of data from a series of online personality tests available [here](http://personality-testing.info/_rawdata/), so you could compare their answers to those from the population at large, find out, and then send me an email. 

* And, finally, something I would have loved as a kid: [the list to end all lists of naughty words.](http://www.infochimps.com/datasets/list-of-dirty-obscene-banned-and-otherwise-unacceptable-words)


## Further Reading

* If you're interested in building predictive models, Max Kuhn's [*Applied Predictive Modeling*](http://www.amazon.com/gp/product/1461468485/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1461468485&linkCode=as2&tag=rsio-20&linkId=MS3S6KTQECYIPVHM) is awesome and I highly recommend it. If you're interested in visualizations, I've heard good things about Tufte's [*The Visual Display of Quantitative Information*](http://www.amazon.com/gp/product/0961392142/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=0961392142&linkCode=as2&tag=rsio-20&linkId=QVRQVSPWKUFU4FJD), but I haven't read it myself. 
* I've written [two](http://rs.io/2014/03/20/creativity-literature-and-compression.html) [posts](http://rs.io/2014/04/04/creativity-fan-fiction-and-literature.html) that use Project Gutenberg data to examine the [link between creativity and compression](http://rs.io/2014/02/22/ju%CC%88rgen-schmidhuber-creativity.html).
* For building visualizations, Excel 2013 has a [new "Power Map" feature](http://blogs.office.com/2013/09/25/power-map-for-excel-earns-new-name-with-significant-updates-to-3d-visualizations-and-storytelling/), which looks dead simple.


## Footnotes
<ol>
<a name="citation-1"></a>
<li>With apologies to JFK: "Let us seek not the Democrat link or the Republican link, but the right link."</li>
<a name="citation-2"></a>
<li>Wikipedia <a href="http://en.wikipedia.org/wiki/KOI-3284.01">says</a>: "KOI-3284.01 is believed to be the most Earth like exoplanet to be found so far by the Kepler space probe. It is predicted to have a radius 1.5 times that of Earth's. It is predicted to be located at the proper distance from the sun to sustain liquid water."</li>
<a name="citation-3"></a>
<li>"The Texas Transportation Institute's latest Urban Mobility Report puts the annual cost of congestion to the nation, including both travel delays and expenditures on fuel, at more than $100 billion."</li>
<a name="citation-4"></a>
<li>If that's not enough, there seems to be a fair amount of research around "murder topology" which is not, as you might naively expect, a super badass branch of mathematics, but rather concerned with the movement patterns of serial murderers.</li>
</ol>
