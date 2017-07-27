

Build size change

```
C:\Users\hasna\Documents\test>npm run build

> test@1.0.0 build C:\Users\hasna\Documents\test
> webpack --entry ./index.js -p --output-filename=./build.js

Hash: b527c8b94f0a46c85437
Version: webpack 3.4.1
Time: 2333ms
     Asset    Size  Chunks             Chunk Names
./build.js  114 kB       0  [emitted]  null
   [5] (webpack)/buildin/global.js 509 bytes {0} [built]
  [11] (webpack)/buildin/module.js 517 bytes {0} [built]
  [26] ./index.js 44 bytes {0} [built]
    + 70 hidden modules

C:\Users\hasna\Documents\test>npm run build:new

> test@1.0.0 build:new C:\Users\hasna\Documents\test
> webpack --entry ./index_new.js -p --output-filename=./build_new.js

Hash: 4934a03daf13d3d53e37
Version: webpack 3.4.1
Time: 1855ms
         Asset     Size  Chunks             Chunk Names
./build_new.js  76.7 kB       0  [emitted]  null
  [22] (webpack)/buildin/global.js 509 bytes {0} [built]
  [30] (webpack)/buildin/module.js 517 bytes {0} [built]
  [82] ./index_new.js 52 bytes {0} [built]
    + 246 hidden modules

C:\Users\hasna\Documents\test>

```