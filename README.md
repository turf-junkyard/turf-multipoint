# turf-multipoint

[![build status](https://secure.travis-ci.org/morganherlocker/turf-point.png)](http://travis-ci.org/morganherlocker/turf-point)

turf multipoint module


### `turf.multipoint(coordinates, properties)`

Creates a MultiPoint based on a
coordinate array. Properties can be added optionally.


### Parameters

| parameter     | type                         | description                                                   |
| ------------- | ---------------------------- | ------------------------------------------------------------- |
| `coordinates` | Array\.\<Array\.\<Number\>\> | an array of Positions                                         |
| `properties`  | Object                       | _optional:_ an Object of key-value pairs to add as properties |


### Example

```js
var multiPt = turf.multipoint([[0,0],[10,10]]);

//=multiPt
```


**Returns** `Feature.<LineString>`, a LineString feature

## Installation

Requires [nodejs](http://nodejs.org/).

```sh
$ npm install turf-multipoint
```

## Tests

```sh
$ npm test
```


