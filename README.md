# AnimXYZ

AnimXYZ helps you create, customize, and compose animations for your website. Powered by CSS variables to allow a nearly limitless number of unique animations without writing a single keyframe. Save time and have complete control over how your elements move. Built for Vue, React, SCSS, and CSS, AnimXYZ will bring your website to life.

# Installation

## Using a package manager

AnimXYZ can be installed using your favorite package manager:

```bash
# with npm
npm install @animxyz/core

# with yarn
yarn install @animxyz/core
```

After installation, you will need to import AnimXYZ into your project.

### Import into a Webpack project
If your Webpack project uses `css-loader` you can import the CSS by putting this snippet anywhere in your javascript code:

```js
import '@animxyz/core'
```

### Import into a SASS project
AnimXYZ is built in SASS and provides useful functions and mixins for customization. Import it anywhere in your SASS code:

```scss
@import '@animxyz/core';
```

---
## Using jsDelivr

To add AnimXYZ using a CDN put this link in the `<head>` of your `index.html` file:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@animxyz/core@0.1.0/dist/animxyz.min.css">
```

---
## Vue & React

 If you are using AnimXYZ in a Vue or React project we strongly recommend you also use our AnimXYZ components. To add those, follow the installation instructions in the relevant sections [Vue](https://animxyz.com/docs/#vue-installation) and [React](https://animxyz.com/docs/#react-installation).
