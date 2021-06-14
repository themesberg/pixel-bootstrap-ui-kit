# [Summer Sale 90% Off All Bootstrap Themes 🏖](https://themesberg.com/summer-sale?ref=github)
[![Summer Sale 90% Off All Bootstrap Themes 🏖](https://themesberg.com/img/campaigns/summer-sale/thumbnail.png)](https://themesberg.com/summer-sale?ref=github)

# [Pixel Bootstrap 5 UI Kit](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fthemesberg%2Fpixel-bootstrap-ui-kit&via=themesberg&text=Kick-start%20development%20with%20Pixel%20Bootstrap%20UI%20Kit&hashtags=bootstrap%2C%20ui%20kit)

 ![version](https://img.shields.io/badge/version-4.0.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/themesberg/pixel-bootstrap-ui-kit.svg?maxAge=2592000)](https://github.com/themesberg/pixel-bootstrap-ui-kit/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/themesberg/pixel-bootstrap-ui-kit.svg?maxAge=2592000)](https://github.com/themesberg/pixel-bootstrap-ui-kit/issues?q=is%3Aissue+is%3Aclosed)

<a href="https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/">
 <img src="https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/pixel-lite-preview.gif" alt="Pixel Bootstrap 5 UI Kit Preview"/>
 </a>

Pixel is a free, fully responsive, modern Bootstrap UI Kit that will help you build creative and professional websites. Use our components and sections, switch some Sass variables to build and arrange pages to best suit your needs.

## Premium components

Pixel is a premium extension of the famous Bootstrap CSS Framework featuring pricing cards, profile cards, timelines and many more and additional plugins for datepickers and input sliders which Bootstrap does not have by default.

Check out [all components here](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit#components).

## Example pages

Pixel comes with 5 example pages that we created to show you the beautiful user interfaces that can be created including a pricing, contact, login and register page.

## Full documentation

Each component, plugin and the general workflow is well documented. Check out the [online documentation for Pixel](https://themesberg.com/docs/bootstrap-5/pixel/getting-started/quick-start/).

## Workflow

This product is built using the following widely used technologies:

- Most popular CSS Framework Bootstrap
- Productive workflow tool Gulp
- Awesome CSS preprocessor Sass

## Table of Contents

* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Demo

| Components | About | Contact | Freelancer |
| --- | --- | --- | --- |
| [![Components](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/all-components.jpg)](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit#components) | [![About page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/about.jpg)](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/html/pages/about.html) | [![Contact](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/contact.jpg)](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/html/pages/contact.html) | [![Freelancer](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/freelancer.jpg)](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/html/pages/landing-freelancer.html)

| Contact | Login | Register | Documentation |
| --- | --- | --- | --- |
| [![Contact page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/contact.jpg)](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/html/pages/contact.html) | [![Login page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/sign-in.jpg)](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/html/pages/sign-in.html) | [![Register page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/sign-up.jpg)](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/html/pages/sign-up.html) | [![Documentation](https://themesberg.s3.us-east-2.amazonaws.com/public/products/pixel-lite/github/docs.jpg)](https://themesberg.com/docs/bootstrap-5/pixel/getting-started/quick-start/)

-   [Live Preview](https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/)
-   [Details](https://themesberg.com/product/ui-kits/pixel-lite-free-bootstrap-4-ui-kit?ref=github-pixel-lite-bootstrap)

## Quick start

1. Download from [Themesberg](https://themesberg.com/product/ui-kits/pixel-lite-free-bootstrap-4-ui-kit?ref=github-pixel-lite-bootstrap)
2. Download the project's zip
3. Make sure you have Node locally installed.
4. Download Gulp Command Line Interface to be able to use gulp in your Terminal.

```
npm install gulp-cli -g
```

5. After installing Gulp, run npm install in the main `pixel/` folder to download all the project dependencies. You'll find them in the `node_modules/` folder.

```
npm install
```

6. Run gulp in the `pixel/` folder to serve the project files using BrowserSync. Running gulp will compile the theme and open `/index.html` in your main browser.

```
gulp
```

While the gulp command is running, files in the `assets/scss/`, `assets/js/` and `components/` folders will be monitored for changes. Files from the `assets/scss/` folder will generate injected CSS.

Hit `CTRL+C` to terminate the gulp command. This will stop the local server from running.

## Theme without Sass, Gulp or Npm

If you'd like to get a version of our theme without Sass, Gulp or Npm, we've got you covered. Run the following command:

```
gulp build:dev
```

This will generate a folder `html&css` which will have unminified CSS, Html and Javascript.

## Minified version

If you'd like to compile the code and get a minified version of the HTML and CSS just run the following Gulp command:

```
gulp build:dist
```

This will generate a folder `dist` which will have minified CSS, Html and Javascript.

## Documentation
The documentation for Pixel Bootstrap UI Kit is hosted on our [website](https://themesberg.com/docs/pixel-bootstrap/getting-started/overview).

## File Structure
Within the download you'll find the following directories and files:

```
Pixel Bootstrap UI Kit
.
├── LICENSE
├── README.md
├── dist
│   ├── assets
│   ├── css
│   ├── html
│   ├── index.html
│   └── vendor
├── gulpfile.js
├── html&css
│   ├── assets
│   ├── css
│   ├── html
│   ├── index.html
│   └── vendor
├── package-lock.json
├── package.json
└── src
    ├── assets
    ├── html
    ├── index.html
    ├── partials
    └── scss
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Resources
- Demo: <https://demo.themesberg.com/pixel-bootstrap-5-ui-kit/index.html>
- Download Page: <https://themesberg.com/product/ui-kits/pixel-lite-free-bootstrap-4-ui-kit?ref=github-pixel-lite-bootstrap>
- Documentation: <https://themesberg.com/docs/pixel-bootstrap/getting-started/overview?ref=github-pixel-lite-bootstrap>
- License Agreement: <https://themesberg.com/licensing?ref=github-pixel-lite-bootstrap>
- Support: <https://themesberg.com/contact?ref=github-pixel-lite-bootstrap>
- Issues: [Github Issues Page](https://github.com/themesberg/pixel-bootstrap-ui-kit/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for Pixel Pro Bootstrap UI Kit. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of Pixel Pro Bootstrap UI Kit. Check the CHANGELOG from your dashboard on our [website](https://themesberg.com?ref=github-pixel-lite-bootstrap).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://themesberg.com/contact?ref=github-pixel-lite-bootstrap) instead of opening an issue.

## Licensing

- Copyright 2020 Themesberg (Crafty Dwarf LLC) (https://themesberg.com)
- Themesberg [license](https://themesberg.com/licensing#mit) (MIT License)

## Useful Links

- [More themes](https://themesberg.com/themes) from Themesberg
- [Free themes](https://themesberg.com/templates/free) from Themesberg
- [Bootstrap Themes, Templates & UI Kits](https://themesberg.com/templates/bootstrap) from Themesberg
- [Affiliate Program](https://themesberg.com/affiliate?ref=github-pixel-lite-bootstrap)

##### Social Media

Twitter: <https://twitter.com/themesberg>

Facebook: <https://www.facebook.com/themesberg/>

Dribbble: <https://dribbble.com/themesberg>

Instagram: <https://www.instagram.com/themesberg/>
