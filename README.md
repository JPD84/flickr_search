# flickr_search project 

About the assignment
We want to propose an assignment that is relevant, challenging and fun, the specs are
intentionally open to avoid constraining creativity, same applies to tools, frameworks
although additional credit will be given when using technologies inline with those mentioned
in the job spec.
Functional requirements
1. the app must use the Flickr API to allow user searching for photos with specific
words.
2. the app must show the results of the search in an infinite scroll list where each cell
contains at least a photo.
3. when tapping on a cell the user of the app must see the full screen photo and its
details.
Non-functional requirements
1. The deliverable must include the full project and a README.txt file describing how to
build it and other relevant information.
2. Any third party library can be used. The README.txt must contain a brief description
of the library and the reason it is used.
3. Even though the app is not an exercise of design, the app must show common UI
techniques and some creativity will be well received.
4. Within the requirements you’re encouraged to add any additional features you find
desirable.

## Project setup
```
navigate to where you want to install the project
```
type 'vue create flickr_search'
```
select 'manually select features' select 'babel','Router', & 'Linter'. 
select 'Yes' for 'use history mode for router'
select 'Airbnb' for 'Pick a linter / formatter config
select 'In package.json' for 'Where do you prefer placing config for Babel, PostCSS, ESLint, etc?'
select 'No' for 'save this as a preset for future projects?'

type 'npm run serve' in terminal to run the app. local address is 'http://localhost:8081' 


npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Third pary libraries and frameworks used
Vue.js library was used at it was best suited for the vue framework and it was one I was familiar with. 

Axios was also used as it works well with the Vue framework and it is one that is recommended for getting propeties from a Flickr API. 

Framework Vue was used because it is one I was most comfortable using.

### Outstanding configurations
I managed to add details to the pictures but not able to have them on full screen when tapped. 

Also having each image neatly composed on the page. 



### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
