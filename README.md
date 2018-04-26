
general pipe for chrome inspector devtools

required nodejs>=6.3.0

go to [chrome://inspect](chrome://inspect)

then anything sent to chrome-inspector's stdin will be shown in the dev tools
tries to parse as json to make use of the devtool's object inspector

`cat - | chrome-inspector`
