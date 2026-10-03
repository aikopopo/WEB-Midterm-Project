# MELORA clothing
 
A multi-page responsive website for a fictional fashion brand that sells party dresses, wedding dresses and clutches. Made for the WEB Technologies Midterm Project.
 
**Authors:** Marzhan & Aigerim
 
**Published website:** _add your GitHub Pages / Netlify link here_
 
## Topic and idea
 
MELORA is an online clothing store. The design idea is "timeless elegance": a lace background, black text, soft beige blocks and large clean photos of dresses. The design was first made in Figma and then built with HTML, CSS and Bootstrap.
 
## Pages
 
| File | Page | What is on it |
|---|---|---|
| `index.html` | Home | Hero screen with a background photo |
| `partydress.html` | Party Dresses | Dress gallery with prices, SALE badges and a 50% off block |
| `bridal.html` | Bridal | Wedding dresses, tabs and a size guide table |
| `clutches.html` | Clutches | Accessories gallery with a large photo in the center |
| `reviews.html` | Reviews | Customer reviews, sign-up form and a big footer |
 
Every page has the same navigation bar at the top, so it is possible to go from any page to any other page.
 
## Features
 
**HTML**
- Semantic HTML5 tags: `header`, `nav`, `main`, `section`, `article`, `footer`
- Headings, paragraphs, links, images with `alt` text
- Lists: menu (`ul` / `li`), benefits list, ordered list
- Table: size guide on `bridal.html`
- Forms: message form (`contact.html`) and sign-up form (`reviews.html`) with labels and input types
- `div` and `span` for structure and styling
**CSS**
- One shared file `style.css` for all pages, split into commented sections
- Classes and IDs (`#hero`, `#promo`, `#contact-form`, `.card-item`, ...)
- Flexbox: menu, hero, promo block, tabs
- CSS Grid: header layout, dress gallery, clutches layout
- Positioning: `position: sticky` for the header, `position: absolute` for the SALE badge and the clutch captions inside `position: relative` cards
- Consistent colors, fonts and spacing across all pages
**Responsive design**
- Media queries for two breakpoints: tablet (`max-width: 992px`) and mobile (`max-width: 576px`)
- Bootstrap 5 grid: `container`, `row`, `col-12 col-md-4`, `col-lg-6` and others
- Bootstrap utilities: `py-5`, `text-center`, `mb-3`, `btn`, `form-control`, `table`, `table-responsive`, `visually-hidden`
## Project structure
 
```
Midterm project/
  index.html
  partydress.html
  bridal.html
  clutches.html
  reviews.html
  style.css
  README.md
  images (jpg / png files, see below)
```
 
Images used: `lace.jpg` (hero background), `dress1.jpg` - `dress6.jpg`, `ballerina.png`, `ballerina2.png`, `bridal1.jpg` - `bridal6.jpg`, `clutch1.jpg` - `clutch5.jpg`, `review1.jpg` - `review3.jpg`.
 
## How to run
 
1. Put all `.html` files, `style.css` and the images in one folder.
2. Open `index.html` in a browser.
Internet is needed to load Bootstrap and the Inter font from a CDN.
 
## How to publish (GitHub Pages)
 
1. Create a new public repository on GitHub.
2. Upload all project files (the files must be in the root of the repository, not inside an extra folder).
3. Open **Settings → Pages**, choose the branch `main` and the folder `/ (root)`, press **Save**.
4. After a minute the site is available at `https://<username>.github.io/<repository>/`. Paste this link at the top of this README.
## Notes
 
- The tabs on the Bridal page (Ball Gown, A-Line, ...) are only visual, they do not filter dresses.
- The forms do not send data anywhere because there is no server part in this project.
- Prices, names and reviews are sample content.
 
