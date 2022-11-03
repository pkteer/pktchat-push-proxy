# PKT Chat Push Proxy

This is a fork of the Mattermost™ Push Proxy with some minor changes to make it work with [PKT Chat iOS](https://apps.apple.com/us/app/pkt-chat/id1645861865?l=en) and [PKT Chat Android](https://play.google.com/store/apps/details?id=com.pktchat.rnbeta) apps.

To compile:

```
go build -o bin ./...
```

To run:

* Edit ./config/mattermost-push-proxy.json to add your Apple and Google tokens from your app release
* Run `./bin/mattermost-push-proxy`

## Free Public Service

A public push proxy is available for anyone running MatterFOSS or Mattermost™ software with pkt.chat apps. This server is available at `the-pusher-man.matterfoss.org` (IPv6 required).

This service is provided by CJDNS SASU as a FREE PUBLIC SERVICE, however the service is provided AS IS with NO WARRANTEES, EXPRESS OR IMPLIED INCLUDING ANY WARRANTEE OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.