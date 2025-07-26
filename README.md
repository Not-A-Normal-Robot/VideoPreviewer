# Video Previewer

A very minimalistic client-side video previewer.

See it in action: https://not-a-normal-robot.github.io/VideoPreviewer/

## Building

### Favicon
To build the favicon, you can minify the original svg using SVGO.

1. Install Node.js: https://nodejs.org/

2. Install SVGO:
```
npm install -g svgo
```
3. Run the optimizer on the favicon:
```
svgo source-assets/favicon.svg -o favicon.svg
```

### Webpage
To build the webpage, you can minify the original html file using `minhtml`.

1. Install Node.js: https://nodejs.org/
2. Install html-minifier:
```
npm i -g html-minifier
```
3. Run the minifier:
```
html-minifier -c minify-html.json source-assets/index.html -o index.html
```