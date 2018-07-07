# React-Express-Starting-Template
Starting template for basic React web app using express server. It is fully setup with webpack, babel, eslint, html-loader, and css-loader. There is a basic express server which is serving the static files and has an empty get request. There is also a React component which is rendered.


### Installing

Install dependencies:

```
npm install
```

Build webpack bundle and start express server (with nodemon)

```
npm start
```

## Check if everything works

Go to localhost:3000 in browser.

If everything is working correctly, there should be red bold text which says "The react App component has rendered!"

If the text is black instead this means the css did not get loaded correctly.

If the text says "This will not display if react component is rendered", then it is just displaying the html which means the react component did not render.


## Acknowledgments

* Copied webpack setup from excellent source here:
https://github.com/clfhhc/sampleMovieList/blob/master/README.md

