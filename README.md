# Contact Sheet Proofing

A Squarespace 7.1 plugin by [Tides Studio](https://tidesstudio.com). Your clients choose their favourite photos on a film contact sheet on your own site, circling each one in grease pencil. Their picks arrive in your inbox through a normal Squarespace Form block.

Buyers get their setup code and the full walkthrough from the member area at tidesstudio.com.

## Install (once per site)

Go to Website → Website Tools → Code Injection → Footer, paste this line and save:

```html
<script src="https://cdn.jsdelivr.net/gh/tidesstudio/contact-sheet-proofing@1.0.0/contact-sheet-proofing.min.js"></script>
```

This needs a Squarespace plan with Code Injection (Core, Plus or Advanced).

## Each proofing page

1. A **Gallery section** holding the proof images.
2. A **Code block** with your settings from the setup page, for example:
   `<div class="tides-proofing" data-choose="15" data-extra-price="25"></div>`
3. A **Form block** with a Text Area field whose label contains the word "Selects".

## Updates

Each version has its own address, so your site only changes when you choose. To update, change the version number in the line above to the latest release.

## Files

- `contact-sheet-proofing.js`: the readable source
- `contact-sheet-proofing.min.js`: the file sites load

© Tides Studio. All rights reserved. Licensed per website to buyers. Please don't share this line with sites that haven't bought it.
