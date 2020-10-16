## aframe-bevelbox-component

A Bevelbox component for [A-Frame](https://aframe.io).

### API

| Property          | Description | Default Value |
| ----------------  | ----------- | ------------- |
|                   |             |               |
| width             |             | 1             |
| height            |             | 1             |
| depth             |             | 1             |
|                   |             |               |
| topLeftRadius     |             | 0.00001       |
| topRightRadius    |             | 0.00001       |
| bottomLeftRadius  |             | 0.00001       |
| bottomRightRadius |             | 0.00001       |
|                   |             |               |
| bevelEnabled      | enable or disable beveling true/false| true          |
| bevelSegments     |             | 2             |
| steps             |             | 1             |
| bevelSize         |             | 0.1           |
| bevelOffset       |             | 0             |
| bevelThickness    |             | 0.1           |


### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.2.0/aframe.min.js"></script>
  <script src="https://rawgit.com/rdub80/aframe-bevelbox-component/master/dist/aframe-bevelbox-component.min.js"></script>
</head>

<body>
  <a-scene>

      <a-entity bevelbox="
                width: 0.5;
                height: 0.5;
                depth: 0.5;

                topLeftRadius: 0.05;
                topRightRadius: 0.05;
                bottomLeftRadius: 0.05;
                bottomRightRadius: 0.05;

                bevelEnabled: true;
                bevelSegments: 10;
                steps: 1;
                bevelSize: 0.05;
                bevelOffset: 0;
                bevelThickness: 0.05;
                " 
      material="color:#EF2D5E;"
      ></a-entity>

  </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-bevelbox-component
```

Then register and use.

```js
require('aframe');
require('aframe-bevelbox-component');
```
