To generate the mac icons:

1. Open the photoshop template and save.
2. Icons should be generated in the Template - App Icon - P3 folder.
3. Grab the 1024x1024 image, and upload it to https://appiconmaker.co/.
4. Download the 16x16, 32x32, 64x64, 128x128, 256x256, 512x512, 1024x1024 icons.
5. Name the icons as follows:

16x16 (1x) -> icon_16x16.png
32x32 (2x for 16x16) -> icon_16x16@2x.png
32x32 (1x) -> icon_32x32.png
64x64 (2x for 32x32) -> icon_32x32@2x.png
128x128 (1x) -> icon_128x128.png
256x256 (2x for 128x128) -> icon_128x128@2x.png
256x256 (1x) -> icon_256x256.png
512x512 (2x for 256x256) -> icon_256x256@2x.png
512x512 (1x) -> icon_512x512.png
1024x1024 (2x for 512x512) -> icon_512x512@2x.png

6. On a mac, add these icons to a folder IconAssets.iconset
7. Run the command iconutil -c icns IconAssets.iconset -o AppIcon.icns
8. Add a copy of AppIcon.icns to the cirkit-create-agent-installer root directory.