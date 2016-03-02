# Reaction Packs

Custom Reaction Packs for Facebook.


## Installation

TODO: Add links to extension pages.


## Contributing

To get started, clone the repository and then run:

```bash
npm install
npm run build:<browser>
```

replacing <browser> with "chrome" or "firefox" as appropriate.


## TODO:

### Extension

* Update pack live instead of requiring a refresh
* Add a status indicator somewhere

### Site

* "Request changes" flow for pack creators.
* Link to pack creator's URL


## Project folder structure:

    # Source code: 
    assets              # Images
    browsers            # Browser specific code
    src                 # Common code across all browsers

    # Build output:
    build               # The raw extension contents for each browser
    dist                # Distributable extension package for browsers
