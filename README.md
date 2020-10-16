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
backblaze.com
bbc.com
blog.cloudflare.com
blog.mozilla.org
bloomberg.com
booking.com
boston.com
bot.land
businessinsider.com
buzzfeed.com
caniuse.com
cbsnews.com
clickup.com
cloudflare.com
cloudinary.com
cnet.com
cnn.com
codewars.com
commitstrip.com
crowdin.com
dailymail.co.uk
datatracker.ietf.org
developer.mozilla.org
digitalocean.com
dilbert.com
doaj.org
dpreview.com
duckduckgo.com
dxomark.com
eff.org
emirates.com
emma-mattress.co.uk
engadget.com
exercism.io
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
geeksforgeeks.org
getzola.org
github.com
glassdoor.com
goodreads.com
gtmetrix.com
gutenberg.org
hackerrank.com
hcaptcha.com
hetzner.com
httpstatuses.com
huffingtonpost.com
hyperoptic.com
ietf.org
ifixit.com
independent.co.uk
indiehackers.com
interviewcake.com
interviewing.io
investor.vanguard.com
iwantmyname.com
joinhoney.com
jsfiddle.net
jsonwebtoken.io
kayak.com
kuantokusta.pt
latimes.com
layoutit.com
leetcode.com
linkedin.com
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
monster.com
mozilla.org
msn.com
namesilo.com
nautil.us
nbcnews.com
netlify.com
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
openstack.org
openwrt.org
overleaf.com
payscale.com
peeringdb.com
peppercarrot.com
poeditor.com
postman.com
postmarkapp.com
protonmail.com
quora.com
realfavicongenerator.net
reuters.com
rightmove.co.uk
salon.com
scientificamerican.com
sendgrid.com
shadow.tech
slate.com
smbc-comics.com
southwest.com
startpage.com
stratechery.com
tailscale.com
tarsnap.com
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
transifex.com
triplebyte.com
tropicalprice.com
typelit.io
ui.com
ukmeds.co.uk
underdog.io
usatoday.com
usnews.com
vanguard.com
vice.com
vox.com
vulnerable.af
vultr.com
washingtonpost.com
wave.webaim.org
webaim.org
webflow.com
whois.domaintools.com
wikibuy.com
worten.pt
wsj.com
xkcd.com
zen.co.uk
```

These are mostly news, travel and shopping websites. I'm planning on increasing the coverage by several orders of magnitude in the near future.

## License

CC-BY-SA 4.0. See `License.md` for further information.
