# Lisboa de quem fica

**An affective, anti-gentrification map of independent, affordable food in Lisbon and on both banks of the Tejo.
** Cafés, tascas, grocers and neighbourhood restaurants for the people who live here and stay here, not for tourism.

The content is in European Portuguese. This is a portfolio piece, not a commercial product.

## The idea

This is not a tourist guide of "must-sees". Pointing crowds at a small family tasca is one of the things that *accelerates* gentrification, so the map deliberately avoids that framing. It is a map of communities and of who keeps a neighbourhood alive: fair prices, real roots, everyday places.

A house earns its place through a simple filter:

- **Independent, not a chain.** Single, often family-run houses over franchises and groups.
- **Fair price, not showcase price.** Neighbourhood prices, judged against what is normal in that area, not inflated "instagrammable" pricing.
- **For residents, not for tourists.** Who the place actually serves.

**The owner's nationality is never a criterion.** 
Immigrant-run independents (Nepalese, Indian, Cape Verdean, Chinese, Mozambican and more) are central to this map, not exceptions. The axis is chain vs. independent and neighbourhood price vs. showcase price.

## What's inside

- ~115 real, verified establishments across 14 municipalities (Lisbon plus the north and south banks of the Tejo).
- Types: tascas, neighbourhood restaurants, grocers (*mercearias*), pastry shops (*pastelarias*), neighbourhood cafés and take-away/grills.
- A stylised SVG map (the Tejo runs across the middle; each municipality is a sardine), filters by municipality and type, a "vegetarian option" badge and filter, and a suggestion form.

## How it works

A single, fully static `index.html`. **No backend, no database, no API keys, no tracking.** It runs anywhere you can host a static file.

The only outbound action is the suggestion form: it opens the visitor's email client (`mailto:`) with a pre-filled message. Nothing is stored or sent automatically. Every suggestion is reviewed by hand before a place is added, which keeps the filter intact.

## Run it

Just open `index.html` in a browser. To publish for free:

- **Netlify Drop** — drag `index.html` onto [app.netlify.com/drop](https://app.netlify.com/drop). Online in seconds.
- **GitHub Pages** — upload `index.html`, then *Settings → Pages → Deploy from a branch → main → / (root)*.

## Data and accuracy

The selection is curated with the help of AI and web research: each place was checked against public sources (its own site and social media, online menus, listings and reviews, local guides and press) and only added once it looked independent and neighbourhood-priced. Nothing is invented and there is no live, automated analysis — everything on the map was reviewed by hand.

Information may still be incomplete or out of date. **Always confirm prices, hours and availability directly with each establishment.** Many neighbourhood cafés and old grocers barely exist online by name; that gap is itself a symptom of what this project is about, and it is exactly what community suggestions are for.

## Credits

Product concept, editorial direction, azulejo design and implementation by Marina. Curation assisted by Claude (Anthropic) and web search. European Portuguese throughout.

## License

Released under the MIT License (code). The curated data is editorial work; please credit the project if you reuse it.
