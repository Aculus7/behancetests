ITCH.IO UPLOAD
1. Create a new itch.io project. Choose HTML as its project kind.
2. Upload this ZIP unchanged and mark it as played in the browser.
3. Set Embed in page, width 1400 and height 1847 (rounded from the original aspect ratio).
4. Disable Click to play, fullscreen button, and scrollbars for a clean desktop presentation.
5. Save and preview. Move the pointer to check the animation.
6. Obtain the playable HTML iframe embed, not the purchase/download widget, and test it in Behance's Embed module.

The original artboard is 1920 x 2533.7099609375. Maintain this aspect ratio when choosing another iframe size. The player uses Contain to preserve the entire artwork; mismatched viewport ratios can leave space.

The archive includes the original export unchanged, a borderless player, and local Rive WebGL2 runtime 2.50.0. Rive's free-export splash is retained. No viewer pan/zoom controls are added. No analytics are included.

Validation: export loaded through Rive runtime; correct artboard and state machine found; six embedded image assets confirmed. Full browser rendering and Behance acceptance still require testing after upload.

Runtime: https://github.com/rive-app/rive-wasm (MIT license).
