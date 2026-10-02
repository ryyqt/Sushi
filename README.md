# Min Sushi & Ramen Bowl

A responsive HTML5 + CSS + Bootstrap 5 recreation based on the supplied design.

## Files

- `index.html` — page structure
- `style.css` — custom styling
- `README.md` — setup notes

## Run

Simply open `index.html` in a browser.

No build tools are required.

Bootstrap 5 and Google Fonts are loaded from their CDNs.

## Customization

The large blank hero section is intentionally kept as a cream background because the supplied screenshot does not show a hero image.

To add a hero image, change `.hero` in `style.css`:

```css
.hero {
    height: 330px;
    background:
        linear-gradient(rgba(246,242,236,.15), rgba(246,242,236,.15)),
        url("images/hero.jpg") center/cover no-repeat;
}
```
