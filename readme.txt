{
  "name": "portfolio",
  "version": "1.0.0",
  "description": "Responsive portfolio website",
  "main": "index.js",
  "scripts": {
    "sass": "node-sass -w scss/ -o dist/css/ --recursive"
      //runs node sass, watches scss folder and outputs 
      //compiled sass to dist folder (recursive to avoid errors)
  },
  "author": "Reece Hawkins",
  "license": "MIT",
  "dependencies": {
    "node-sass": "^4.9.3"
  },
  "devDependencies": {}
}

//bash to initiate bash in the console, same for node. 
//Run sass when compiling and editing