# 3D Rotation Converter
A simple HTML+JavaScript page to convert between different 3D rotation formats, quaternions, Rodrigues angles, Euler angles, etc.

__Run http://www.andre-gaschler.com/rotationconverter/ directly to convert rotations online__

## Dependencies
Most of the conversion is calculated with the [three.js library](https://github.com/mrdoob/three.js) (which is also MIT-licensed).

## License
Permissive MIT license, see file LICENSE

## Build
To generate the minified math part of three.js, call
`python three.js-master/utils/build/build.py --include math --minify --output three-onlymath.min.js`
