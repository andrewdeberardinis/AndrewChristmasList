# Andrew's Christmas List

A one-page Christmas wish list with a spinning gift wheel, a flying minecart sleigh,
and a "Can you afford it?" popup.

## Run it
Open `index.html` in any web browser. No install or build step needed.

## Edit the gifts
In `index.html`, find `const GIFTS = [` and add or change entries:

    { name: "Gift name", price: 49.99, show: "$49.99", url: "https://..." },

- `price` sets the hidden weight (pricier gifts come up more often).
- `show` is the price text shown on the page.
- `url` is optional; leave it out for "your pick" items.

## Built with
Plain HTML, CSS and JavaScript (canvas for the wheel, snow and confetti; inline SVG
for the sleigh and mountains) plus Google Fonts.
