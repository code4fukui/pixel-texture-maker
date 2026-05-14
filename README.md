# pixel-texture-maker

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

https://code4fukui.github.io/pixel-texture-maker/

A browser-based tool for generating procedural pixel art textures using simplex noise and color gradients.


![Screenshot of the pixel-texture-maker application interface](https://user-images.githubusercontent.com/1715217/199686410-83bce132-7b56-46b4-b30f-0630d6a75897.jpg)


## Features

- **Customizable Palettes:** Define a color gradient using the provided color pickers.
- **Multiple Color Spaces:** Interpolate colors in RGB, LAB, LCH, HSV, HSL, or HSI color spaces for different visual effects.
- **Noise Control:** Adjust the texture's appearance with intuitive sliders for contrast and animation offset.
- **Animation:** Watch the texture evolve over time. Animation is enabled by default and can be toggled.
- **Standalone:** Runs entirely in a modern browser with no installation required.

## How to Use

Open `index.html` or visit the demo link to use the generator. The interface consists of a 256x256 pixel canvas (composed of 16x16 blocks) and several controls:

- **Color Pickers:** Click to change the colors that form the texture's gradient.
- **Mode Dropdown:** Select the color space used for gradient interpolation.
- **Top Slider (Contrast):** Adjusts the distribution of colors by changing the exponent applied to the noise value.
- **Bottom Slider (Time Offset):** Manually scrubs through the noise pattern. This slider is disabled when animation is active.
- **Animation Button:** Toggles the automatic animation on and off.

## Libraries Used

This project utilizes the following open-source libraries:

- [chroma-es](https://github.com/code4fukui/chroma-es): A lightweight library for color conversions and scales.
- [simplex-noise.js](https://github.com/jwagner/simplex-noise.js): A fast simplex noise implementation, loaded via [SkyPack CDN](https://cdn.skypack.dev/).

## License

Texture data created by this application can be used freely.