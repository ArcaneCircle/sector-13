# SECTOR 13

SECTOR 13 is a hectic space shooter built for Mobile and Desktop devices.
Touch/Click and drag to move your ship.

## Story

Commander, it is all up to us!

Thirteen sectors and untold legions of enemy ships...

All that stands between us and our final victory...

We are scared, but our fear makes us strong!

We are scared, but we have faith in your abilities!

We are scared, but we will emerge victorious!

## Contributing

### Installing Dependencies

After cloning this repo, install dependecies:

```
pnpm i
```

### Checking code format

```
pnpm check
```

### Testing the app in the browser

To test your work in your browser (with hot reloading!) while developing:

```
pnpm start
# Alternatively to test in a more advanced WebXDC emulator:
pnpm emulator
```

### Building

To package the WebXDC file:

```
pnpm build
```

To package the WebXDC with developer tools inside to debug in Delta Chat, set the `NODE_ENV`
environment variable to "debug":

```
NODE_ENV=debug pnpm build
```

The resulting optimized `.xdc` file is saved in `dist-xdc/` folder.

### Releasing

To automatically build and create a new GitHub release with the `.xdc` file:

```
git tag -a v1.0.1
git push origin v1.0.1
```

## Credits

This is a port to Webxdc of [SECTOR-13](https://github.com/BenjaminWFox/Sector-13-Js13k-2024) originally written by [BenjaminWFox](https://github.com/BenjaminWFox) for [js13k 2024](https://js13kgames.com/) game jam

### Acknowledgements

[Frank Force](https://twitter.com/KilledByAPixel) for [ZzFX](https://github.com/KilledByAPixel/ZzFX)

[Keith Clark](https://twitter.com/keithclarkcouk) and [Frank Force](https://twitter.com/KilledByAPixel) for [ZzFXM](https://keithclark.github.io/ZzFXM/)

[Kenney](https://kenney.nl/) for [Pixel Platformer](https://kenney.nl/assets/pixel-platformer) graphics

[Andrzej Mazur](https://end3r.com/) for organizing js13k
