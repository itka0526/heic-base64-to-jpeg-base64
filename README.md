# heic-base64-to-jpeg-base64

If there any errors with 'node-canvas' please visit https://www.npmjs.com/package/canvas, they have great about error handling documentaion! I had a small hiccup because my mac was ARM64.

Turned https://github.com/ricokahler/heic.app this guy's project to an express API

Usage:
  send a POST request to this URL: 
  https://heic-base64-tojpeg-base64.herokuapp.com/convert_heic_base64_to_png_base64
  
  with body: 
          [
            {
             name: "any1.heic",
             type: "image/heic",
             size: "294 kB",
             base64: "data:image/heic;base64.....",
             file: {},
            },
            {
             name: "any2.heic",
             type: "image/heic",
             size: "294 kB",
             base64: "data:image/heic;base64.....",
             file: {},
            },
            {
             name: "any3.heic",
             type: "image/heic",
             size: "294 kB",
             base64: "data:image/heic;base64.....",
             file: {},
            }
          ]
    
  
  
