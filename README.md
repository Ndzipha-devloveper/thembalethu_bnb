# Thembalethu BnB

A responsive static website for Thembalethu BnB in Thembalethu, George.

## Features

- Scrolling announcement bar with official booking details and seasonal offers.
- Animated Christmas tree with glowing star and twinkling colored lights.
- Responsive branded header, hero photo carousel, and accommodation details.
- Amenity icons, photo gallery, booking enquiry form, and contact links.
- CSS motion effects that respect the user's reduced-motion preference.

## Project structure

```text
thembalethu_bnb/
├── index.html       # Page content and inline SVG illustrations
├── css/
│   └── style.css    # Layout, responsive styling, and animations
├── js/
│   └── script.js    # Page interactions
└── backend/
    └── .gitkeep     # Reserved for future backend code
```

## Run locally

No build step or external frontend dependencies are required. From the project
directory, start a local server:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>. The `backend/` directory is only a placeholder;
no backend framework or server-side functionality is configured yet.
