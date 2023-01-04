

## Chatper 2 
Covered below topics
### Parcel 
* Creates dev server 
* HMR - Hot module replacement 
* File Watcher algorithm - C++
* Bundling 
* Minify
* Cleaning our code
* Dev and production build
* super fast build algorithm
* Image Optimization
* Caching while development 
* Compression
* Compaitable with older version of browser
* HTTPS on Dev
* port number
* consistent hasing algorithm
* Zero config

* Dependency tree
* Transitive Dependencies 

### Browserslist 
* Makes code compaitable for all browsers
* Add in package.json
* browserslist.dev

### To create React project 
    npm init -y 

### To install parcel
    npmt i -D parcel 
    -D - to install only in Dev (aka devDependencies)

### To Execute a project 
    npx parcel <entry point of file>
    npx parcel index.html

### .gitignore
* Add .parcel-cache, node_modules 

### .parcel-cache folder
* Creates cached entries - can't be opened 

### dist folder
    minified version of the app that can be deployed 

### node_modules 
* All dependecies are installed here 
    
    `<script type="module" scr="App.js"></script>`

//Type: module - because we need to use import statement 

    import React from "react"
    import ReactDOM from "react-dom/client"
