To see the project working, you need to serve it from a server so the assets can be downloaded e.g `npx http-server --cors -g . `

To inject it from another project, you can mimic index.html and add the scripts and angular identifier to your page.
You might need to modify window.env.ASSETS_URL="" in `env.js` to match the route in which you put the "iberia-web-content" folder.
If you have any issues with the proper labels being printed properly due to CORS or similar, don't worry, it is not the point in the challenge.
If you have issues injecting this component, or have any other application that prefer to showcase, feel free to use it. The main thing that we want to see in the challenge is the injection of a web application.