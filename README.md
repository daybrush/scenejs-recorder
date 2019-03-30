# scenejs-render [![npm version](https://badge.fury.io/js/scenejs-render.svg)](https://badge.fury.io/js/scenejs-render)



Make a movie of CSS animation through [scenejs](https://github.com/daybrush/scenejs).
## Installation
```bash
$ npm install scenejs-render
```

## Usage
```js
$ render -i index.html --name scene
```

```
  Usage: render [options] [command]
  
  Commands:
    help     Display help
    version  Display version
  
  Options:
    -c, --cache <n>       you can pass Capture. (0: false, 1: true) (defaults to 0)
    -d, --duration        how many seconds to play
    -f, --fps <n>         fps (defaults to 60)
    -h, --height <n>      Video height to render (defaults to 400)
    -H, --help            Output usage information
    -i, --input [value]   File URL to Rendering (defaults to "index.html")
    -m, --media [value]   Name of mediaScene to render (defaults to "mediaScene")
    -n, --name [value]    Name of scene to render (defaults to "scene")
    -o, --output [value]  Output file name (defaults to "output.mp4")
    -p, --port <n>        Port to Rendering (defaults to 3033)
    -s, --startTime <n>   Time to start (defaults to 0)
    -v, --version         Output the version number
    -w, --width <n>       Video width to render (defaults to 600)
```
## Result
```
Start Rendering
Start Capture (startTime: 0, endTime: 2, fps: 60, startFrame: 0, endFrame: 171.42857142857144)
Capture frame: 0, time: 0
Capture frame: 1, time: 0.011666666666666665
Capture frame: 2, time: 0.02333333333333333
Capture frame: 3, time: 0.034999999999999996
Capture frame: 4, time: 0.04666666666666666
Capture frame: 5, time: 0.058333333333333334
Capture frame: 6, time: 0.06999999999999999
...
frame: 71, time: 0.8283333333333333
Capture frame: 72, time: 0.84
Capture frame: 73, time: 0.8516666666666666
Capture frame: 74, time: 0.8633333333333333
Capture frame: 75, time: 0.875
Capture frame: 76, time: 0.8866666666666666
Capture frame: 77, time: 0.8983333333333333
Capture frame: 78, time: 0.9099999999999999
Capture frame: 79, time: 0.9216666666666666
Capture frame: 80, time: 0.9333333333333333
...
Capture frame: 101, time: 1.1783333333333332
Capture frame: 102, time: 1.19
Capture frame: 103, time: 1.2016666666666667
Capture frame: 104, time: 1.2133333333333334
...
Capture frame: 170, time: 1.9833333333333332
Capture frame: 171, time: 1.9949999999999999
Capture frame: 172, time: 2
Convert Audio ./test.mp3
Convert Audio ./test2.mp3
Merge Audios
Processing start (totalframe: 172, duration: 2.857142857142857, fps: 60)
Processing: 0% done
Processing: 0.5780346820809249% done
Processing: 9.971098265895954% done
Processing: 21.38728323699422% done
Processing: 41.47398843930636% done
Processing finished !
End Rendering(Rendering Time: 62.248s)
```