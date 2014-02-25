# geolitecity

This is the Maxmind Geo Lite City data and stored as the file ```GeoLiteCity.dat```. It is intended for testing purposes with packages like [geoip-stream](https://github.com/angleman/geoip-stream) and so the data may become stale and hence it is recommended fresh data be obtained from [Maxmind GeoLiteCity](http://dev.maxmind.com/geoip/legacy/geolite/).

## Install

```bash
npm install geolitecity
```

## Usage

```js
var GeoIpStream = require('geoip-stream');
var geoStream   = new GeoIpStream({ dataFile: './node_modules/geolitecity/GeoLiteCity.data' })
```

## License

Dual licenses:

- This package without data: MIT
- Geo Lite City data: [Creative Commons Attribution-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-sa/3.0/) as per [Maxmind GeoLiteCity](http://dev.maxmind.com/geoip/legacy/geolite/)
