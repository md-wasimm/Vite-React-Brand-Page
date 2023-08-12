# Vite-React-Brand-Page

First vite react project.

Live link -  https://md-wasimm.github.io/Vite-React-Brand-Page/

# Deploy in Github Pages -

Just follow these simple steps:

1. Install the gh-pages package (ctrl+~ to open the terminal in VS Code) -
npm install gh-pages --save-dev
2. In the package.json file add these lines before "build": "vite build", -
"predeploy": "npm run build",
"deploy": "gh-pages -d dist",
3. In the vite.config.js file add this line before plugins -
base: "/YOUR_REPOSITORY_NAME",

4. In terminal type -
npm run deploy
