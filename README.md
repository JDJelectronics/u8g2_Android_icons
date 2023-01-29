# u8g2_Android_icons

The workflow to create an icon for displays, do the following steps:

Open Gimp (install first: https://www.gimp.org/downloads/)
Find an icon on a site like (flaticon), download it, and open it in Gimp
Selecteer Image-->Mode-->Indexed-->Use black and white (1 bit) palette
Scale to correct size (16x16 of 32x32 etc.)
If the icon needs improvement, after scaling. Then touchup the icon.
Touch up icon:
6. Select the 'perceel brush'
7. Left to the brush (links), select the 1 pixel brush
8. Change the size to the 1 pixel
9. Touch up your icon to your liking

Remove Alpha Transpancy Layer:
10. Remove transparency layer (Layer --> Transpancy --> Remove Alpha Layer)

Exporteer icon to XBM format
11. File --> Export as (CTRL-E)
12. Enter a new name, ending in '.xbm'
13. Open the result in notepad, then you can find:

Code example in xmb format

#define flame_16x16_width 16
#define flame_16x16_height 16
static unsigned char flame_16x16_bits[] = {
0x80, 0x00, 0x80, 0x00, 0x80, 0x01, 0xc0, 0x01, 0xc0, 0x01, 0xc0, 0x03,
0xe0, 0x0b, 0xf0, 0x0f, 0x70, 0x1f, 0x78, 0x1e, 0x38, 0x1e, 0x38, 0x1c,
0x18, 0x1c, 0x18, 0x1c, 0x30, 0x0e, 0x20, 0x07 };

Icon pack android 12 status bar

![image](https://user-images.githubusercontent.com/16858919/143130290-67cb535d-7be4-42a2-865f-6fe857871160.png)
![image](https://user-images.githubusercontent.com/16858919/142770997-35cdd05c-045d-42bb-ab1f-fa30d024b537.png)

