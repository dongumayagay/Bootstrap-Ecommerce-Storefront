# Bootstrap Ecommerce Storefront

To view a live preview hold **Ctrl** and click
[here](http://bootstrap-ecommerce.vercel.app/).  
The site will open in a new tab.  
alternatively you can also right click the link above to open the live preview

**Screenshots folder** contains screenshots of the homepage in different screen sizes.

**assets folder** for now just contains the thumbnail of dummy products use in the site. since we are not yet in the backend.

The task at hand focus on Bootstrap and by that source file just has index.html in it and it uses Bootstrap for the styling. Decided to use the CDN link to reduce the size of the project and speaking of reducing the size every thumbnail also has average size of 50kb again for smaller project size that will be upload to Teams, it also help the loading time of the page in the live preview.


## Requirements
- Node.js

## Developing

start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

```bash
npm run build
```

> You can preview the built app with `npm run preview`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.
