![Alt text](https://raw.githubusercontent.com/simonwalton/spermglyphs/master/resources/public/assets/img/logo_logo.png)

## Synopsis

This project is an implementation of the glyph design contained within the paper [Glyph-Based Video Visualization for Semen Analysis](http://www.ncbi.nlm.nih.gov/pubmed/24344092). As well as providing an example implementation of drawing the glyph from its parameters as described in the paper, the system includes many other features to provide exploration of the parameter space and the ability to choose from a number of presets.

This work was developed partly to demonstrate our glyph design effectively to accompany its presentation at VIS 2014 in Paris, France. 

## Features

- Manual adjustment of glyph parameters with real-time feedback
- The ability to compare multiple instantiated glyphs
- A variety of animal and human presets
- A parallel coordinates visualization built with d3.js to explore the parameter space
- The ability to save parameter configurations and share them via a short URL

## Cloning and Running 

Our implementation is in Clojure/Clojurescript, and [leinigen](http://leiningen.org). Once the repository is cloned, use

`lein deps`

To fetch all of the dependencies. Then, run:

`lein ring server`

To start a localhost server instance with the codebase running. Or, you can create a big .jar containing all dependencies that'll execute a Jetty instance when run:

`lein uberjar; java -jar target/<compiledjarfile>.jar`

## Contributors

A huge thankyou to Eamonn Macguire, Alfie Abdul-Rahman, and Min Chen for their help with testing. 

## License

Our code is licensed under GPL v3. Please see LICENCE for details. Some aspects have a separate licence. In particular, the images used for the animal presets are creative commons licenced, and we include their attributions on the web application interface and in the image directory itself inside a text file.
