# sveltemeacoffee
Fully Configurable Buy Me A Coffee button in svelte

## Why does this exist?

When trying to use the [Buy Me A Coffee](https://www.buymeacoffee.com/) button, I noticed there are a few things wrong with the buttons you can create:

1. There are only a handful of colored images to choose from.
1. If you try to use a custom color or text, you can't get an image link for that custom value.
1. If you try to use the script code they give you, it fails in Svelte/Kit (and maybe Nuxt, etc, as well)with the following error:

  >  Failed to execute 'write' on 'Document': It isn't possible to write into a document from an asynchronously-loaded external script unless it is explicitly opened. 

## Options:
There are SVG images in the BMAC creator kit, so I used those to create a SVG image of the button and used the svg `translate()` for scaling.

### Defaults:

