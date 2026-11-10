# Sourjya Mukherjee — Personal Portfolio

A responsive, dark minimalist portfolio built with plain HTML, CSS and vanilla JavaScript.

## Run locally
1. Extract the project ZIP.
2. Open `index.html` in a modern browser.

No build tools, package manager or server are required. An internet connection is only needed to load the optional Google Fonts; the site otherwise works locally.

## Files
- `index.html` — page structure and portfolio content
- `styles.css` — visual design and responsive layouts
- `script.js` — mobile menu, active section navigation, reveal effects and footer year

## Add chess gallery photographs
In `index.html`, find the `gallery-grid` section. Replace each `.gallery-placeholder` element with an image, for example:

```html
<div class="gallery-photo">
  <img src="images/chess-event-01.jpg" alt="Chess tournament photograph">
</div>
```

Then add this CSS to `styles.css`:

```css
.gallery-photo {
  aspect-ratio: 4 / 3;
  overflow: hidden;
  background: #181818;
}
.gallery-photo img {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: cover;
}
.gallery-photo:first-child {
  aspect-ratio: 16 / 9;
}
```

Create an `images` folder beside `index.html` and place your photographs there. Keep alt text descriptive without naming people in the photographs.

## Before publishing
- Confirm that all personal details and ratings are current.
- Test the contact and profile links.
- Add your own gallery photographs.
- Upload the folder contents to your chosen static website host.

## Note about the WhatsApp link
The link is set exactly as supplied: `https://wa.me/sourjyaa`. WhatsApp's public `wa.me` links generally expect a phone number in international format, so verify that this username-based URL resolves as intended before publishing.
