FloatKit
Floating Social Sidebar Widget


Package Structure
floatkit/
|- dist/
|  |- floatkit.css
|  |- floatkit.min.css
|  |- floatkit.js
|  `- floatkit.min.js
|- demo/
|  `- index.html
|- documentation/
|  `- index.html
|- index.html
`- README.txt

Quick Start
1) Add CSS in <head>:
   <link rel="stylesheet" href="dist/floatkit.min.css">

2) Add container in <body>:
   <div id="floatkit-widget"></div>

3) Add JS before </body>:
   <script src="dist/floatkit.min.js"></script>
   <script>
   FloatKit.init({
     position: 'left',
     theme: 'solid',
     networks: [
       { id: 'facebook',  url: 'https://facebook.com/yourpage' },
       { id: 'instagram', url: 'https://instagram.com/yourhandle' },
       { id: 'twitter',   url: 'https://x.com/yourhandle' }
     ]
   });
   </script>

Main Options
- container: CSS selector for mount node (default '#floatkit-widget')
- position: left | right | top | bottom | bottom-left | bottom-right
- theme: solid | glass | outline | glow | minimal | light
- shape: rounded | circle | sharp | square
- size: sm | md | lg | xl
- blur: true/false
- showLabels: true/false
- hideMobile: true/false
- mobileMoveBottom: true/false
- scrollHide: true/false
- scrollHideOffset: number
- networks: array of { id, url, label?, count? }

Links
- Demo: demo/index.html
- Documentation: documentation/index.html
