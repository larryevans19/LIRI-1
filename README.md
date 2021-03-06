# LIRI

![Build Status](https://img.shields.io/badge/LIRI-node-ff69b4.svg?style=for-the-badge&logo=npm)

>Liri is a Language Interpretation and Recognition Interface that searches for songs, concerts, movies or random action on a random file.

## Table of contents

* [General info](#general-info)
* [Setup](#setup)
* [Examples](#examples)
* [Technologies](#technologies)


## General info

Liri is a command line node app that takes in parameters and generates back data by sending requests using the axios package to the Bands in Town, Spotify and OMDB APIs. By using API calls and parsing through returned JSON objects, we can output them in a specified format.

## Setup

Liri requires [Node.js](https://nodejs.org/) v4+ to run.

Install npm package manage and dependencies then input desired commands.

```sh
$ cd liri
$ npm install
$ node liri.js
```

#### Find Concerts

```sh
$ node liri.js concert-this '<artist/band name here>'
```

#### Find Songs

```sh
$ node liri.js spotify-this-song '<song name here>'
```

#### Find Movies

```sh
$ node liri.js concert-this '<movie name here>'
```

#### Do What It Says

```sh
$ node liri.js do-what-it-says
```

## Examples

![Example screenshot](img/concert.gif)
![Example screenshot](img/spotify.gif)
![Example screenshot](img/movie.gif)
![Example screenshot](img/dowhatitsays.gif)

## Technologies

* [Node.js](https://nodejs.org/)- evented I/O for the backend
* [JavaScript](https://www.javascript.com/)
* [NPM](https://www.npmjs.com/) - Package manager
* [Spotify-API](https://developer.spotify.com/documentation/web-api/) - API library for Spotify
* [BandsinTown-API](http://www.artists.bandsintown.com/bandsintown-api) - API library for Bands/Artists
* [OMDB-API](https://www.omdbapi.com/) - API library for movies

