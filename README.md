# Rotation Converter
Simple HTML+JS page to convert between different 3D rotation formats, quaternion, Rodrigues angles, etc.

*You can run https://cdn.rawgit.com/gaschler/rotationconverter/master/converter.html directly to convert rotations online*

## Dependencies
Most of the conversion is calculated with the three.js library (which is also MIT-licensed).
https://github.com/mrdoob/three.js

## License
Permissive MIT license, see file LICENSE

## Build
To generate the minified math part of three.js, call

   python three.js-master/utils/build/build.py --include math --minify --output three-onlymath.min.js
