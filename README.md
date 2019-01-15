# (Ubuntu) Snap for WoTT Agent

Packages the WoTT Agent into a Snap.


## Installing

```
$ snap install wott-agent
```

## Building (locally)

```
$ snapcraft cleanbuild
```


## Release management

 * Push changes and bump up the version
 * Visit [this launchpad page](https://code.launchpad.net/~vpetersson/wott-agent/+git/wott-agent) and press "Import Now"
 * When the code base has successfully been refreshed above, visit [this page](https://code.launchpad.net/~vpetersson/+snap/wott-agent) and select 'Request builds'
 * When the builds are done, they will automatically be published to the Candicate channel in the Snap store. You can then promote the Candidate release to Stable on [this page](https://snapcraft.io/wott-agent/releases)
