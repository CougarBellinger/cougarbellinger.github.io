# Cougar Bellinger's personal website

This is a static website built with Astro and hosted on GitHub Pages.

## Local setup

1. Install [Node.js 24 LTS](https://nodejs.org/), which includes npm.
2. Clone the repository and enter its directory:

   ```sh
   git clone https://github.com/CougarBellinger/cougarbellinger.github.io.git
   cd cougarbellinger.github.io
   ```

3. Install the exact dependencies from the npm lockfile:

   ```sh
   npm ci
   ```

4. Start the development server:

   ```sh
   npm run dev
   ```

Run `npm run build` to generate the production site in `dist/`, or
`npm run preview` to preview that build locally.