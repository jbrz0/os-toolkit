# Odd Scenes Web Toolkit

A lightweight & fast frontend website build tool.

Built on the middleman framework. Includes a bunch of modern frontend tools.

### Setup
1) Install
- Xcode CLI Tools: `xcode-select --install`
- `gem install middleman`
2) Create your site with dev server
- Run `middleman init project-name` (project-name is folder name)
- Navigate to `project-name`
- Start up dev server: `middleman server`
- Now you can make changes and build the site
3) Build to production
- When ready run `middleman build`
- Project files to be used are located in `/build` folder
4) Deploy with NOW
- Ensure you have NodeJS installed: [here](https://nodejs.org/en/download/)
- Run: `npm install -g now`
- Navigate to build folder: `cd build`
- Run `now` (verify email address on first time)
- Your website will now be live at the URL given

__You can also use the files in `/build` on your own server__


+(TODO) - ADD DESCRIPTION

### Dependencies

- Middleman: Static site generator
- Bootstrap 4: UI toolkit
- jQuery: JS functionality

+(TODO) Velocity - Animation library
+(TODO) jQuery UI / Mobile ???


### Features

- ERB templates
- Components (partials)
- ES6 + polyfill support
- Live reloading
- Minified, fast production build
- SEO optimized
- Sitemap generated with production build
- Single build command will properly build all files
- No server config/routing needed
- Easily deploy to Now, Netlify or other one click systems

+(TODO) CSS Grid
+(TODO) SASS + mixins, structure setup

---

### Meta Information Variables

- Default `<meta>` tag properties are located in `/data/meta.yml`
- If specified in template some of these values will be ignored

---

### Google analytics

- Default code for analytics is located in `/javascripts/analytics.js`

---

Built by [http://oddscenes.com](http://oddscenes.com)