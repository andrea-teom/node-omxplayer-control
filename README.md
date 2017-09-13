# node-omxplayer-control

forked from oeuillot/node-omxplayer

## Objective

Control omxplayer by node API
Add windows size and position parameter

## Installation

    $ npm install https://github.com/andrea-teom/node-omxplayer-control.git

## Usage

Launch omxplayer :
```javascript
var configuration = {};
var omxplayer = new OMXPlayer(configuration);

omxplayer.start("movie.mkv", function(error) {
});

omxplayer.on("playing", function() {
	
});

omxplayer.on("stopped", function() {
	
});


```
