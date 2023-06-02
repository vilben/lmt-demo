# check

`lmt check example.html`

`lmt check --web https://wikipedia.org`

# suggest

`lmt suggest http://hsr.ch/Studium.60.0.html`

`lmt check example.html | lmt suggest --input-format json`

# fix

`lmt check example.html | lmt suggest --input-format json | lmt fix example.html`

`lmt fix example.html`
