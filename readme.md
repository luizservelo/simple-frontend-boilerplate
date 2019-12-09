# Simple Frontend Boilerplate

## About Simple Frontend Boilerplate
Simple Frontend Boilerplate is an open source initiative to automate and expedite the start of frontend web projects.
Now, feel free to use this structure as you wish and I will be happy to receive feedback.
Let's code!

## DevTools
1. Node | npm
2. SASS | node-sass & nodemon
3. jQuery

## File Structure
<pre>
📦simple-frontend-boilerplate
    ┣ 📂assets
    ┃ ┣ 📂css
    ┃ ┃ ┗ 📜style.css
    ┃ ┣ 📂images
    ┃ ┃ ┗ 📜favicon.png
    ┃ ┣ 📂js
    ┃ ┃ ┣ 📜jquery.js
    ┃ ┃ ┗ 📜scripts.js
    ┃ ┗ 📂scss
    ┃ ┃ ┗ 📜style.scss
    ┣ 📜.gitignore
    ┣ 📜index.html
    ┣ 📜package.json
    ┗ 📜readme.md
</pre>
## Using SASS
1. Install Node.js
2. Run this command from your terminal at project root. <pre>npm install</pre>
3. Then, run... <pre>npm run watch-css</pre>

Now just edit the *assets/scss/style.scss* file and it will compile your minified styles in *assets/css/style.css*