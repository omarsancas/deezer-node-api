# Deezer API wrapper

This is *Nodejs* wrapper for the [Deezer API](http://developers.deezer.com/api) that return promises.

## Installation
    npm install deezer-node-api --save

## Usage example
``` JavaScript
var Deezer = require('deezer-node-ap');
var dz = new Deezer();

dz.getAlbum(302127).then(function(album) {
    console.log(album);
});
```

## Available methods
* getAlbum(albumId)
* getArtist(artistId)

## Testing
    npm test