# uBlock & uMatrix Rulesets

Personal uBlock & uMatrix rulesets.

Please note that the uBlock rulesets are very opinionated.
The uMatrix recipes are built assuming the following default rules:

```
no-workers: * true
* * * block
* 1st-party css allow
* 1st-party image allow
* 1st-party frame allow
```

These are more restrictive than the ones proposed by uMatrix.

## Highlights

These lists were adapted from my personal rulesets and are being actively improved with semi-automated spider bots.

The malware list includes hosts serving viruses, ransomware, scareware, badware, cryptocoin miners, scams and some forms of spyware. Most adware and spyware is filled under `ads-tracking`.

## Actively Monitored Websites

While these lists block ads, tracking and malware on websites all over the web, I'm currently monitoring several websites for new potentially malicious hosts:

```
abcnews.go.com
allsides.com
arstechnica.com
assets.time.com
bbc.com
blog.cloudflare.com
blog.mozilla.org
bloomberg.com
booking.com
boston.com
businessinsider.com
buzzfeed.com
cbsnews.com
cnet.com
cnn.com
dailymail.co.uk
doaj.org
eff.org
emirates.com
engadget.com
expedia.com
farefirst.com
feedly.com
flightics.com
flightradar24.com
flytap.com
foxnews.com
gawker.com
goodreads.com
gutenberg.org
huffingtonpost.com
independent.co.uk
indiehackers.com
kayak.com
latimes.com
lwn.net
mashable.com
meetup.com
mic.com
migueldemoura.com
mirror.co.uk
mises.org
mlive.com
momondo.com
msn.com
nautil.us
nbcnews.com
news.ycombinator.com
nj.com
nydailynews.com
nypost.com
nytimes.com
postmarkapp.com
reuters.com
salon.com
scientificamerican.com
slate.com
southwest.com
stratechery.com
techcrunch.com
technologyreview.com
telegraph.co.uk
textslashplain.com
theatlantic.com
theblaze.com
thedailybeast.com
theguardian.com
theregister.com
usatoday.com
usnews.com
vice.com
vox.com
vulnerable.af
washingtonpost.com
worten.pt
wsj.com
```

These are mostly news, travel and shopping websites. I'm planning on increasing the coverage by several orders of magnitude in the near future.

## License

CC-BY-SA 4.0. See `License.md` for further information.
