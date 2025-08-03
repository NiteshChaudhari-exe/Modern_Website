# Legends Society – Modern React Website

A modern, responsive website built with React, Vite, and Tailwind CSS. Features include smooth navigation, animated UI components, and a clean design system.

## Features

- React 19 + Vite for fast development and HMR
- Tailwind CSS for utility-first styling
- Scroll lock for mobile navigation
- Responsive header and navigation menu
- Custom SVG assets and gradients
- Modular component structure

## Getting Started

### Install dependencies

```sh
npm install
```

### Run in development mode

```sh
npm run dev
```

### Build for production

```sh
npm run build
```

### Preview production build

```sh
npm run preview
```

### Lint the code

```sh
npm run lint
```

## Project Structure

```
src/
  assets/        # Images and SVGs
  components/    # React components
  constants/     # Static data and config
  index.css      # Global styles
  main.jsx       # App entry point
public/
  vite.svg       # Public assets
index.html       # HTML template
```

## Customization

- Update navigation links in [`src/constants/index.js`](src/constants/index.js)
- Add or modify assets in [`src/assets`](src/assets)
- Edit styles in [`src/index.css`](src/index.css) and [`tailwind.config.js`](tailwind.config.js)

## Credits

- Inspired by the [React + Vite](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react) template
- Icons by [Heroicons](https://heroicons.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)
