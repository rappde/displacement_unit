# DISPLACEMENT_UNIT

A brutalist signal processor for analog-style glitches and displacement mapping.

## 01_OVERVIEW
This tool distorts pixels based on luminance data. It allows for high-precision spatial manipulation using source imagery, video, or live camera feeds.

## 02_FEATURES
- **REAL-TIME DISPLACEMENT:** Distort X and Y axes via luminance maps.
- **MULTI-INPUT:** Support for Image, Video, and Live Webcam.
- **CUSTOM MAPS:** Upload secondary images to drive distortion patterns.
- **EXPORT:** Save high-res PNG stills or record MP4 video directly in the browser.
- **PRIVACY:** 100% local processing. No data is uploaded to any server.

## 03_USAGE
1. **LOAD SOURCE:** Upload an image/video or start the Live Cam.
2. **LOAD MAP:** (Optional) Upload a custom displacement map. If empty, the tool uses the source image as its own map.
3. **ADJUST PARAMS:** 
   - `X_STRENGTH`: Horizontal shift.
   - `Y_STRENGTH`: Vertical shift.
   - `THRESHOLD`: Luminance gate for the effect.
4. **EXPORT:** Save the result as a still or record a video sequence.

## 04_DEVELOPMENT
Built with vanilla JavaScript and HTML5 Canvas. Part of the Demien Rapp design system.
- **Font:** Space Grotesk
- **Colors:** #000, #FFF, #FF0000

## 05_CREDITS
MADE BY [RAPPDE.COM](https://rappde.com)
DEVELOPED BY **DEMIEN RAPP**

