# Maliha Azizi — Portfolio

A responsive personal portfolio for **Maliha Azizi**, a graphic designer and motion & animation designer. The site presents selected branding, illustration, motion, and visual-design projects in a clean, editorial layout.

## Highlights

- Responsive portfolio and project-detail views
- Image and video project showcases
- Project gallery with navigation and carousel interactions
- Video playback controls and hover previews
- Configurable typography and portfolio content through the included Element SDK integration
- Contact form with client-side validation for name, email address, and message
- Email delivery through FormSubmit, with enquiries sent to `malihaazizi17@gmail.com`

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- [Tailwind CSS Play CDN](https://tailwindcss.com/docs/installation/play-cdn)
- Font Awesome icons
- Google Fonts

## Project Structure

```text
.
├── assets/       # Images, videos, logos, and portfolio media
├── index.html    # Page structure and portfolio content
├── style.css     # Custom styles and animations
├── script.js     # Interactions, project data, form validation, and UI behavior
└── README.md
```

## Run Locally

No build step or package installation is required.

1. Clone the repository.
2. Open `index.html` in a browser, or serve the folder with a local development server.

For example, with VS Code, use the **Live Server** extension and open the project folder.

## Contact Form Setup

The contact form posts submissions to FormSubmit and includes the visitor's name, email address, and message. Before delivery begins, FormSubmit requires a one-time confirmation for the recipient address.

1. Submit the form once from the deployed site.
2. Open the confirmation message sent to `malihaazizi17@gmail.com`.
3. Confirm the address.

After confirmation, new form submissions will be delivered to that inbox. The email destination is configured in `index.html` in the form's `action` attribute.

## Deployment

Because this is a static website, it can be deployed to GitHub Pages, Netlify, Vercel, Cloudflare Pages, or any standard web host. Upload the full project directory, including `assets/`, `style.css`, and `script.js`.

## License

This portfolio and its creative assets are intended for Maliha Azizi's personal use. Do not reuse the artwork, videos, or written content without permission.
