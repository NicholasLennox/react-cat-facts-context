# Cat Facts App

A simple React app that fetches random cat facts from the [Cat Facts API](https://catfact.ninja/). You can save facts to a favourites list and view them on a separate page.

Built to practice Context API, custom hooks, and service layers in React.

## Post-class improvements

**NavLink instead of Link**
Swapped React Router's `Link` for `NavLink` so the active page is automatically highlighted in the navbar.

**Nicer navbar**
Added a cat icon/brand that links to home, left-aligned the nav links with some spacing between them, and extracted the active class logic into a reusable function.

**Favourites feedback**
When you add a fact to favourites, the button disables and a short confirmation message appears. Both reset when a new fact is loaded so you can't accidentally add the same fact twice.

## How to run

```bash
# Install dependencies
npm install

# Start the dev server
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173) in your browser.