
# Periodic Table

A simple web project that displays the periodic table of elements using only HTML.

## Features

- Clean and colorful representation of the periodic table.
- No JavaScript or CSS dependencies—pure HTML.
- Easily deployable as a static site (configured for Firebase Hosting).

## Project Structure

```
.
├── firebase.json         # Firebase Hosting configuration
├── public/
│   └── index.html        # Main HTML file with the periodic table
└── README.md             # Project documentation
```

## Live Demo

View the live site: [https://periodic-table-ecf7e.web.app](https://periodic-table-ecf7e.web.app)

## Deployment

This project is set up for Firebase Hosting. To deploy:

1. Install Firebase CLI if you haven't:
   ```bash
   npm install -g firebase-tools
   ```
2. Log in to Firebase:
   ```bash
   firebase login
   ```
3. Deploy the site:
   ```bash
   firebase deploy
   ```