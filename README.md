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

These lists were adapted from my personal rulesets and are being actively improved with semi-automated spider bots. The host lists are particularly comprehensive in the following areas:

* [Admiral](https://getadmiral.com) domains
* Game currency/key generator scams

The malware list includes hosts serving viruses, ransomware, scareware, cryptocoin miners, scams and some forms of spyware. Most adware and spyware is filled under `ads-tracking`.

## License

CC-BY-SA 4.0. See `License.md` for further information.
