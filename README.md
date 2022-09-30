# Lean 4 Natural Number Game web interface


This is a prototype web interface for the Lean 4 version of the [Natural Number Game
(NNG)](https://www.ma.imperial.ac.uk/~buzzard/xena/natural_number_game/)
of Kevin Buzzard and Mohammad Pedramfar. 
See the [NNG4 repository](https://github.com/PatrickMassot/NNG4) for more information.

Building this requires a [npm](https://www.npmjs.com/) toolchain. After cloning the repository you should run
`npm install` to pull in all dependencies. Then you want to modify the line of `src/App.js` which defines
the `socketUrl` variable (there will be a more convenient procedure at some point). For install you can use
`localhost` there to play locally. 

In order to build the website, run `npm run build`. Then copy the content of the newly created `build` folder to some place where your webserver can find it. For quick experimentation (and for development) you can run `npm start` that will perform a non-optimized build and then run a local webserver on port 3000.
