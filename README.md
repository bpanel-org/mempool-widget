# Mempool Widget

A simple widget for the [bPanel Dashboard plugin](https://github.com/bpanel-org/dashboard). The mempool
widget decorates the secondary widget area below the larger primary area. Order of widgets in secondary area
will depend on the order in which the widget plugins were installed.

The widget relies on the [chain sockets](https://github.com/bpanel-org/chain-sockets) plugin to subscribe
to new transaction events via websockets. TX count and mempool size will increase (and decrease) as new transactions
are received and blocks found.

![screenshot](https://raw.githubusercontent.com/bpanel-org/mempool-widget/master/screenshot.png "Mempool Widget screenshot")

(Note: you cannot actually make transactions cheaper by clicking a button. The button in the widget has no actual effect.)