# web-mqtt-client
> A better MQTT API for the browser


Motivation
----------

- Paho offers clunky API
- MQTT.js browserified is large
- neither works completely intelligently re: subscriptions etc


Features
--------

- wraps Eclipse Paho
- no own dependencies
- only x KB, y minified, z, min + gz



Roadmap
-------

- [] randomly generated clientIds
- [] subscribe / unsubscribe API
- [] publish API
- [] lwt support
- [] test coverage x
- [] minfied build
- [] public release npm/bower
- [] MQTT topic regex support
- [] separate messages event API
- [] extended connection lifecycle callbacks
- [] reconnection callback
- [] rewrite Paho Errors
- [] proper linting config
- [] test coverage x
- [] filter subscription/unsubscription calls to broker if topic has other callbacks
- [] filter sub/unsub is QoS-aware
- [] automatic resubscription of topics on reconnect


Notes
-----

- Paho documentation http://www.eclipse.org/paho/files/jsdoc/index.html
- promise support for methods? or example for wrapping
- debug: paho/client lib may swallow errors and interrupt js execution, page unresponsive without error msgs ( typo assign undefined keyword )


Colophon
--------

- microevents.js