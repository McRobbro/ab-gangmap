Anti_Backstory Territory map
====
[Live page](https://rockysouthpaw.github.io/ab-gangmap/)
This interactive (Google) map shows you the location of current Anti-Backstory territory/gang zones.

## Screenshots

![screenshot-1](https://i.imgur.com/VavAdiG.jpg)

![screenshot-2](https://i.imgur.com/978UDPW.jpg)

![screenshot-3](https://i.imgur.com/ijtZIHO.jpg)

![screenshot-4](https://i.imgur.com/VMuDSrK.png)

## How to submit new locations
1. Go to locations.json and copy the HIGHEST id element, then increase the ID number by one.
2. Set colors, notes, video/image, etc.
3. Put this code in the browser console to show the "print location array" button: `$("#createzone").removeClass("hidden");`
4. Right click to place markers around the outline of the territory (Place in order around, or else it will be a weird shape)
5. Press the Print location array button and copy the output from the console, paste that for the latlngarray in locations.json
6. Submit an Issue or Pull Request with the new location, and I'll add it to the main page :)
![screenshot-5](https://i.imgur.com/40cSiK4.png)

## How to host yourself

1. Clone this repository
2. [Download the missing map tiles](https://mega.co.nz/#!HR1xgIQQ!I2cq1hDeWfm6A3BleDfOlTz747EpCUlX15tCt1h2IN8) and extract them into an folder called "tiles/"
3. Run `python -m SimpleHTTPServer` in the source folder if you don't have an Nginx/Apache
3.b Python 3 run `python -m http.server`

## License

[WTFPL](LICENSE)

## Version

1.0

## Credits

To [danharper](https://github.com/danharper/) for [his work](https://github.com/danharper/GTAV) on the GTA V map.
To [gta5-map](https://github.com/gta5-map) for [their work](https://github.com/gta5-map/gta5-map.github.io) on the GTA V map.
To [skyross}(https://github.com/skyrossm/np-gangmap) for [their work} on the map.
