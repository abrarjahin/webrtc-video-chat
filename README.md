WebRTC & SignalR Video Chat
=================

[Live Demo](https://mg-webrtc.azurewebsites.net)

A demo project for playing around with Peer-to-Peer audio/video connections using [WebRTC](https://webrtc.org/).

Signaling and management of users and active connections is handled by [SignalR](https://www.asp.net/signalr) .

At the time of writing this, the application is working in the following browser releases:

- [Google Chrome](https://www.google.co.in/chrome/browser/desktop/) (26.0.1410.3)
- [Firefox](https://www.mozilla.org/en-US/firefox/new/) (22.0)
- [Opera](http://www.opera.com/) (42.0)
- Android Browser (5.3)
- [Chrome for Android](https://play.google.com/store/apps/details?id=com.android.chrome&hl=en) (55.0)

** [Edge](https://www.microsoft.com/en-us/windows/microsoft-edge), [IE](https://www.microsoft.com/en-us/download/internet-explorer.aspx) and [Safari](http://www.apple.com/safari/) can also use WebRTC by using [*this*](https://confluence.temasys.com.sg/display/TWPP) or [this](https://skylink.io/plugin/) plugin.

More can be found [**here**](http://caniuse.com/#search=webrtc).

However, the WebRTC implementation is progressing in upper mentioned browsers, so this may or may not be broken by the time you try to use it :)

- Rough around the edges
- Connections take a LONG time in Firefox.  Be patient, it will (probably) work if you didn't get a bunch of JavaScript errors.
- Currently limited to two callers on the line at once.  Conferencing is in the works.