# satoshisearch
 
Fairly simple little scraper and vocabulary analyser of the https://www.metzdowd.com cryptography mailing list archives where Satoshi first posted the Bitcoin whitepaper.

Blog post: https://jamesbachini.com/search-for-satoshi/ 

## Methodology:

Scrape all the messages from Satoshi after November 2008.

Remove common words with an english word list and manually

Rescrape the archives prior to November 2008 to see who uses similar words and phrases.

Additional weight on very unique words that are uncommon and not likely to be widely used by a broad range of people.

## Criticism:

This is a fairly low sample size analysis. More data could be pulled from the whitepaper and other known posts/emails. Perfectly plausible that Satoshi was a lurker and never posted before. More detailed analysis either with machine learning or sentence structure would be more conclusive.

## Conclusion:

- 8 - Linda Casals
- 10 - Hal Finney
- 4 - Joshua Hill
- 4 - Jeff.Hodges at KingsMountain.com
- 7 - Leichter, Jerry
- 5 - Anne & Lynn Wheeler
- 6 - bear
- 4 - pgut001 at cs.auckland.ac.nz
- 5 - Guus Sliepen
- 5 - alex at alten.org
- 4 - Daniel Carosone
- 4 - auto37159 at hushmail.com
- 6 - zooko
- 8 - Crawford Nathan-HMGT87
- 7 - R.A. Hettinga
- 5 - Ray Dillinger
- 8 - David Wagner
- 4 - Eric Young

#### Hal Finney is the closest match to Satoshi Nakamoto.

No major surprises or revalations here. Hal has always been one of the most likely suspects and this just adds a bit more weight to that case. I was hoping to find a British candidate as spelling alternates between US and British English at times, something I do myself when writing for a more US audience but I've never seen Americans adjust their English before.

Hal was always suspected because of him being the first person other than Satoshi to take an interest. An elderly gentlemen named Dorian 'Satoshi' Nakomoto lived a couple of blocks away from Hal and it's believed this is where the alias came from as it's a unique name. Hal was also the only person to write something possitive about the original whitepaper post. He was also the first receiver of a bitcoin transaction etc.

From this analysis Hal's use of words that Satoshi also uses like "pseudonymous" are quite unique, even for a cryptography group.

I also ran the data for post-2008 which could well be corrupted by who's talking about the same tech after the paper had been released and Hal got the second highest score on that behind Ray Dillinger. Ray Dillinger was also the bear profile above and he was involved in auditing the code. Makes sense that he would be using the same terminology after the release.

Unfortunately Hal died in 2014 but his legacy remains.

https://en.wikipedia.org/wiki/Hal_Finney_(computer_scientist)

Could Hal have been working with someone else like Ray or Nick Szabo? Quite possibly, there's certainly a case for Satoshi having a British link which is unclear with Hal.


## Installation:
```
apt install nodejs;

apt install npm;

npm install request;

npm install request-promise;

node satoshisearch.js;
```
