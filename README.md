# hvr-simulator
Slightly altered HVR simulator package from https://github.com/AdrielCodeops/HurricaneVR-Extensions

Downloaded version: 2.0.0


# Changes

- All three .cs files got the #if GUZ_HVR_INSTALLED pragma, that they will only be handled if GameSettings HVR is activated (and HVR is installed). Otherwise we would get compile time errors if HVR isn't in Assets path
- Added package.json file
- .cs files from /Core moved to /Runtime to reflect unity Package Manager structure
- Added .meta files where neccessary