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
    └── src/main/java/com/ungasokoli/
        ├── dto/        # Enquiry request and response types
        ├── exception/  # Enquiry-related exceptions
        ├── model/      # Booking enquiry model and status
        ├── repository/ # Booking enquiry repository contract
        └── service/    # Enquiry and availability service types
```

## Run locally

No build step or external frontend dependencies are required. From the project
directory, start a local server:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>. The `backend/` directory contains Java type
skeletons only; no backend framework or server-side functionality is configured yet.
