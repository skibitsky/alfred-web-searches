# Alfred Web Searches [![Workflows](https://img.shields.io/badge/-more%20workflows-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://github.com/learn-anything/alfred-workflows) [![Thanks](http://bit.ly/saythankss)](https://github.com/sponsors/nikitavoloboev)

> [Alfred](https://www.alfredapp.com/) workflow to search through any website (easily extendable list)

<img src="https://i.imgur.com/IxhwjuN.png" width="500" alt="img">

This workflow similar to [DuckDuckGo Bangs](https://duckduckgo.com/bang?) allows you to fuzzy search through a selection of websites that you can [add and contribute to](workflow/websites.csv).

You simply search for the website you want to scope your search too, press enter and make your search.

Some results have a prefix to signify the scope of the search. For example results prefixed with `r:` will search through Reddit subreddits. Here is the full list of prefixes and their descriptions.

| Prefix | Description                   |
| ------ | ----------------------------- |
| r:     | Search subreddits on Reddit   |
| d:     | Search documentation websites |
| g:     | Search GitHub                 |
| s:     | Search stack exchange sites   |
| f:     | Search forums                 |
| t:     | Search Google Translate       |

Each prefix also has a corresponding icon for visual feedback of prefix meaning.

And since the workflow allows for fuzzy searching, you can even make searches like that:

<img src="https://i.imgur.com/eekNFrr.png" width="500" alt="img">

And they will match.

You can also attach a hotkey that will take the selected text and then will let you search for that text on any of the websites.

## Install

Download workflow from [GitHub releases](../../releases/latest).

See [here](https://github.com/deanishe/awgo/wiki/Catalina) for instructions on fixing permissions in macOS refusing to run Go binary.

## Contributing

See [contribution guidelines](contributing.md).

## Thank you

You can support me on [GitHub](https://github.com/sponsors/nikitavoloboev) or look into [other projects](https://nikitavoloboev.xyz/projects) I shared.

[![MIT](http://bit.ly/mitbadge)](license) [![Twitter](http://bit.ly/nikitatweet)](https://twitter.com/nikitavoloboev)
