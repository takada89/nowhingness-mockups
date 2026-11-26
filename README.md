# Nowhingness Mockups: first version

A mockup maker that runs in your phone's browser. Pick a piece from your gallery, choose a scene and a size, and save the result to your phone. Nothing is uploaded: the images never leave your phone.

## What it does

- **10 scenes, all drawn in code** (no stock photos, so there are no licence issues): Framed on wall, Dark room glow, Phone screen, Gallery (with a wall label), Taped poster, Desk print, Tablet, Laptop, Desktop monitor, Clean border.
- **Art size slider** makes the piece bigger or smaller in any scene.
- **Device screens are filled by default.** Drag the preview to choose which part of the art shows. The phone turns sideways for landscape art. Switch off "Fill the screen" to show the whole piece instead.
- **4 sizes:** Instagram 4:5 (1080×1350), Square (1080×1080), Story/Reel (1080×1920), Twitter/X 16:9 (1600×900).
- **Carousel set:** saves 3 slides in one go: the full piece on a clean border, a close-up detail (tap the small picture to choose where, and use the slider to zoom), and the scene you chose.
- **Branding:** a "NOWHINGNESS" signature you can turn on or off, in three styles (CAPS, Script, mono) and three positions. Your choices are remembered.
- **Colours come from your art.** The "Auto" wall, the phone background and the dark-room glow use colours taken from the piece.
- **My photo:** pick a photo of your own wall, desk or screen, then drag the 4 pink corners to place your art in it with real perspective. It has an optional frame and a slider that lets the photo's light show on the art.
- **Caption & hashtags:** builds an Instagram or X caption from your title, mood and the app you used, plus a call to action. It picks 5 specific hashtags (Instagram's limit since Dec 2025), shuffled so that recently used ones come last. It also has one-tap copy and a simple weekly posting plan. It works offline, with no AI service.

## Putting it on your Android phone

**Option A (recommended): free web link, installed like an app.**
After it's hosted (for example on GitHub Pages or Netlify, both free), open the link in Chrome, tap ⋮ and then **Add to Home screen / Install app**. It opens full screen and also works offline. *Not done yet: this needs your OK, because the page would be public (your art would not be, since nothing is uploaded).*

**Option B: open the file directly (no hosting).**
1. Copy the whole `mockup-maker` folder to your phone (USB, Google Drive, and so on).
2. Open **Files**, find `index.html`, and open it with **Chrome**.
3. Bookmark it. (This can't be installed as an app, and some Android versions won't open local files in Chrome. Use option A if that happens.)

## Saving images

Tap **Save image** or **Save carousel (3)**. A preview opens:
- **Save to phone** puts the JPGs in Downloads, and they show up in Gallery / Google Photos.
- **Share** sends them straight to an app such as Instagram, X or Drive.

## Tested

Tested in Chromium emulating a Pixel 7: every scene in every size with portrait, landscape and square art, the carousel export (3 files at the correct pixel sizes), settings being remembered after a reload, and offline install when hosted. There were no errors. It has not been tried on your actual phone yet.
