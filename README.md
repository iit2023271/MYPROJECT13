# AI Image Generator (Front-End)

A front-end for an AI image generator: enter a text prompt and it shows the generated image below the form.


## Screenshot

![Demo](screenshots/demo.png)

## Features

- Text prompt input
- Generate Image button
- Generated-image display area with a caption
- Validation for an empty input field

## Tech Stack

- HTML
- CSS
- JavaScript

## How to Run

Just open `index.html` in any browser. No build step, no server needed.

```bash
# or serve it locally
python3 -m http.server
# then open http://localhost:8000
```

## Important note — the API is a placeholder

The fetch URL in the code is literally `use a API` — it is **not** a real image-generation endpoint, so clicking Generate does not return an image out of the box. To make it functional, replace that URL with a real image API endpoint (and an API key if the service needs one). The screenshot shows the form UI as it stands.
