# EliteHomes

EliteHomes is a responsive real estate landing page built with HTML, CSS, and
Bootstrap 5.3.8. It features property listings, real estate services, client
testimonials, frequently asked questions, and a contact section.

## Demo :
https://taha20353.github.io/elitehomes/

## Extra features and improvements

- Clickable property photos open detailed Bootstrap modals with listing photos,
  prices, home features, agent information, and email inquiry links.
- Property heart buttons toggle their selected state.
- Five service tabs switch content with Bootstrap fade transitions.
- The testimonial carousel supports autoplay, arrows, indicators, and touch
  swiping, with a stable height between slides.
- Mobile navigation uses Bootstrap Offcanvas, with a collapsible property menu
  and a hamburger icon that changes to a close icon.
- FAQ answers expand and collapse, and navigation highlights the current section
  using Bootstrap ScrollSpy.
- CSS hover effects add image zoom, card movement, and button feedback, while
  respecting reduced-motion preferences.
- Responsive layouts, keyboard-friendly controls, and native HTML form
  validation improve usability across screen sizes.

All interactive behavior uses Bootstrap's official bundle through HTML data
attributes. No custom JavaScript is used. Images and Bootstrap files are stored
locally.

## Structure

```text
index.html
favicon.png
images/
style/
vendor/bootstrap/
```

Open `index.html` in a browser or serve this folder with a local static server.

The contact form and chat are demonstration interfaces without a backend. The
form does not send messages, and property favorites are not saved after reload.
