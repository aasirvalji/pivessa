# Pivessa website

Static marketing, support, and privacy pages for Pivessa. The published repository
contains the website and its public media, rather than the native app's source.
No dependencies, build step, analytics, remote fonts, or advertising.

- Marketing: https://aasirvalji.github.io/pivessa/
- Support: https://aasirvalji.github.io/pivessa/support/
- Privacy: https://aasirvalji.github.io/pivessa/privacy/

GitHub Pages publishes the `main` branch at `/`. `.nojekyll` enables plain static
serving. Keep paths relative so all pages work under the `/pivessa/` project URL.
Videos and screenshots show the actual native application. The preview is silent.

Run `python3 -m http.server 8765` from this directory to preview locally.

The app hasn't been submitted or released by this website deployment. Add a real
App Store download URL and update the availability copy once it is released.
