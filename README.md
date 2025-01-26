<<<<<<< Updated upstream
# stars
LupineVault star background taken from [Shadow Tunnel](https://shadowtunnel.vercel.app/)

Demo at [GitHub Pages](https://lupinevault.github.io/stars/)
=======
# Stars.js
Easy stars background with html, js, and css

## Instructions

To easily put a star background on ***any*** site, follow these instructions:

    1. Right after the first ```<body>``` tag, paste ```<canvas id="canvas"></canvas>```
    
    2. Right before the last ```</body>``` tag, paste ```<script src="stars.js"></script>```
    
    3. In your CSS file, paste the following at the end:
    
    ```
    /* Stars */
#canvas {
    display: block;
    position: fixed;  /* Cover the viewport */
    top: 0;
    left: 0;
    width: 100vw;  /* 100% of the viewport width */
    height: 100vh; /* 100% of the viewport height */
    
    pointer-events: none; /* Prevents canvas from interfering with interactions */
}
    ```
    
    4. Put the stars.js file in the same directory as the HTML file with the stars
    
    5. Enjoy!
>>>>>>> Stashed changes
