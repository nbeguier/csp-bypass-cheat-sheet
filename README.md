# CSP Bypass Cheat Sheet

[![License](https://img.shields.io/github/license/nbeguier/csp-bypass-cheat-sheet?color=blue)](https://github.com/nbeguier/csp-bypass-cheat-sheet/blob/master/LICENSE)

This is a webpage that give the working payload for a given CSP. It's hard to understand the impact by juste reading the CSP rules, this page is trying to execute every payload and display the command in cas of success. 

## Prerequisites

None

## Usage

```bash
# Run a local webserver in the current directory
$ python -m http.server 5000

# Go to http://localhost:5000/
```

Here, you can see all working payload with the defined CSP.
You can change it by uncomment/comment the `index.html` file.
From line 22 to 52.
There is:

- No CSP
- Script Unsafe Inline via Event Attribute
- Script Unsafe Inline via iFrame
- Script Data
- Script GoogleAPIs
- Script Cloudflare CDN
- Script Predictable Nonce
- Script Self
- No Script
- Styles Self
- Default Predictable Nonce
- NOTHING

Then, some example from famous websites:

- CSP Evaluator safe policy
- Github
- Paypal
- Twitter

# License
Licensed under the [Apache License](https://github.com/nbeguier/csp-bypass-cheat-sheet/blob/master/LICENSE), Version 2.0 (the "License").

# Copyright
Copyright 2021 Nicolas BEGUIER; ([nbeguier](https://beguier.eu/nicolas/) - nicolas_beguier[at]hotmail[dot]com)
