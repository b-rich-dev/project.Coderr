# Coderr/ Frontend Project

![Coderr Logo](assets/logo/logo_coderr.svg)

This project is a simple frontend built with **Vanilla JavaScript** (pure JavaScript without frameworks). It was specifically designed to help students of the **Developer Akademie** with backend experience get started with smaller frontend customizations.

---

## Prerequisites

- A running Django backend (`Coderr/`), which is **not** included in this project.
- Visual Studio Code with the **Live Server** extension or a similar way to run `index.html` locally in the browser.

---

## Usage

1. Make sure the backend `Coderr/` is running.
2. Open this project in **Visual Studio Code**.
3. Right-click on `index.html` and select **Open with Live Server** to start the project.

---

## Project Goals

This frontend was intentionally built with **Vanilla JavaScript** to achieve the following goals:

- **Easy entry point**: By avoiding frameworks like React or Angular, the code remains easy to understand and follow.
- **Learning through customization**: Students can modify the code to make small changes and better understand frontend concepts.
- **Backend integration**: The project can easily be connected to the existing Django backend `Coderr/`.

---

## Notice

This project is **exclusively intended for students of the Developer Akademie** and is not released for free use or redistribution.

**Attribution:** Developed as part of the training program of Developer Akademie GmbH.

For parts provided by the Developer Akademie, the attached license applies: see LICENSE.md (Developer Akademie Learning License, Non-commercial).

---

## Error Monitoring with Sentry

This project uses **[Sentry](https://sentry.io)** to automatically capture JavaScript errors in the browser.

Sentry is integrated via the CDN loader in all HTML pages:

```html
<script src="https://js-de.sentry-cdn.com/619696dcf340ca3d19964a09007d1b19.min.js" crossorigin="anonymous"></script>
```

Errors are automatically forwarded to the Sentry dashboard and can be viewed there under **Issues**. No further configuration or installation is required.

---

## JSDoc - View

1. Navigate to the `docs/` folder.
2. You can open the project by double-clicking `docs/index.html`, or in the terminal:
    Windows: `start docs/index.html`
    macOS: `open docs/index.html`
    Linux: `xdg-open docs/index.html`
