# android-emulator-skins

These Android Emulator Skins replace the bleaky default look with high quality graphics of actual devices and feature a reflection overlay, too.

The repostory contains these skins

 * Galaxy Nexus
 * Nexus S
 * Nexus One
 * Nexus One Silver (light version of the original)
 * Nexus One Black (dark version of the original)

## Installation

Copy the desired skins to the appropriate platform's skin directory below your Android SDK, e.g.

`<path-to-android-sdk>/platforms/android-X/skins/GALAXY-NEXUS`

Where X is the [API level](http://developer.android.com/guide/appendix/api-levels.html) of Android you would like to use these skins with.

## Usage

All skins had been designed with respect to the original display resolution of the devices. This is great for taking screenshots or producing a screencast but rarely matches a laptop's screen. When running on the emulator consider a scaling option, e.g.

`-scale 0.5`

Also, every skin comes with an overlay expands the reflection of the body above your screen content. Use the onion feature of the emulator to enable this, e.g.

`-onion-alpha 100 -onion <absolute-path-to-skin>/overlay.png`

These skins had been built by Heiko Behrens ([http://HeikoBehrens.net](http://HeikoBehrens.net)) based on graphics by Alexander Gillis ([http://zandog.deviantart.com](http://zandog.deviantart.com)).

Galaxy Nexus Skin by Aaron Snoswell ([http://elucidatedbinary.com](http://elucidatedbinary.com))

Happy Coding!