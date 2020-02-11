# Spotify Publishers

**Table of Contents**

- [Getting Started](#getting-started)
- [Client](#client)
  - [CSS](#css)
  - [JS](#js)

# Getting Started
This page has been developed statically and there are no build steps needed to deploy this application to the web. Enjoy!

** NOTE **
Since this application was developed statically, outside of the current Java environment, we had to mock the current structure of the app based on http://publishers.spotify.com/guide/your-music. This could mean there are bugs hiding, as the assumption was that we could rely on CSS and markup already included in the app. Please also note that there is no Hero or Footer in the markup as it seems redundant to include it. See below for additional info.

# Client

## CSS
A note on `main.css`: I've included the CSS taken from [https://publishers.spotify.com/static/css/main.css?v=10](https://publishers.spotify.com/static/css/main.css?v=10) which I've specified in a comment at the bottom. This can be removed and was for the purposes for testing the css outside of the current environment. `bootstrap.css` can also be removed as well as the import from `index.html`. We used some bootstrap classes for tooltips and responsive containers. Otherwise, the css is mobile first, so the classes at the top of `main.css` will be for mobile and you'll find various other breakpoints throughout.

## JS
JS was used sparsely; only for initializing the tooltips for the app.
