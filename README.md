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
aa.net.uk
abcnews.go.com
airbnb.com
allsides.com
anandtech.com
arstechnica.com
assets.time.com
bbc.com
blog.cloudflare.com
blog.mozilla.org
bloomberg.com
booking.com
boston.com
bot.land
businessinsider.com
buzzfeed.com
cbsnews.com
cnet.com
cnn.com
commitstrip.com
dailymail.co.uk
dilbert.com
doaj.org
dpreview.com
dxomark.com
eff.org
emirates.com
emma-mattress.co.uk
engadget.com
expedia.com
fakespot.com
farefirst.com
fastmail.com
feedly.com
flightics.com
flightradar24.com
flytap.com
forwardemail.net
foxnews.com
gawker.com
github.com
goodreads.com
gutenberg.org
huffingtonpost.com
hyperoptic.com
ifixit.com
independent.co.uk
indiehackers.com
joinhoney.com
kayak.com
kuantokusta.pt
latimes.com
lwn.net
mailgun.com
mashable.com
meetup.com
mic.com
migueldemoura.com
mirror.co.uk
mises.org
mlive.com
momondo.com
monkeyuser.com
msn.com
nautil.us
nbcnews.com
news.ycombinator.com
nj.com
notebookcheck.com
notebookcheck.net
noticiasaominuto.com
nydailynews.com
nypost.com
nytimes.com
octopus.energy
openrent.co.uk
overleaf.com
peppercarrot.com
postmarkapp.com
protonmail.com
reuters.com
rightmove.co.uk
salon.com
scientificamerican.com
sendgrid.com
shadow.tech
slate.com
smbc-comics.com
southwest.com
stratechery.com
techbargains.com
techcrunch.com
technologyreview.com
telegraph.co.uk
textslashplain.com
theatlantic.com
theblaze.com
thedailybeast.com
theguardian.com
theoatmeal.com
theregister.com
tropicalprice.com
ui.com
ukmeds.co.uk
usatoday.com
usnews.com
vice.com
vox.com
vulnerable.af
washingtonpost.com
wikibuy.com
worten.pt
wsj.com
xkcd.com
zen.co.uk
```

These are mostly news, travel and shopping websites. I'm planning on increasing the coverage by several orders of magnitude in the near future.

## License

CC-BY-SA 4.0. See `License.md` for further information.
