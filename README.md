# Mini Museum: The Red Fox Exhibit (AR Activity)

A marker-based WebAR scene built with A-Frame and AR.js. Point your phone at the
Hiro marker and a small natural-history exhibit appears: an animated red fox on a pedestal,
a spinning gold ring, a colour-changing orb and an information sign.


## Testing on a phone

1. Open the HTTPS URL on your phone (Safari on iOS, Chrome on Android) and allow the camera.
2. Point the camera at the Hiro marker. The banner turns green and the exhibit appears.
3. Tap the orange orb: it cycles through colours.
4. Tap the fox: it grows on each tap and shrinks back after the third.
5. Tap the white sign: the caption hides; tap again to show it.
6. Cover the marker: the banner turns red.

## Credits

**Fox model:** "Fox" from the [Khronos glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/Fox).

- Model: PixelMannen, 2014, [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/legalcode)
- Rigging and animation: tomkranis, 2014, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode)
- Conversion to glTF: AsoboStudio and scurest, 2017, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode)

The file is used unmodified.

**Hiro marker image:** from [AR.js](https://github.com/AR-js-org/AR.js) (MIT licence).

**Libraries:** [A-Frame](https://aframe.io) (MIT), [AR.js](https://ar-js-org.github.io/AR.js-Docs/) (MIT),
[aframe-extras](https://github.com/c-frame/aframe-extras) (MIT) for the `animation-mixer` component.
