
items i made. Both their decompiled .png versions and .item versions.

Compiled versions are ordered as they would be when put on "Items" folder of sfd

Decompiled versions are ordered by layer in the code as it was more comfortable for me.

# Included packs

- [Chambafighters](https://www.moddb.com/games/superfighters-deluxe/addons/chambafighters)
  
![ssss](https://media.moddb.com/images/downloads/1/266/265364/chf.jpg "CHF thumbnail")

- [Gore Improvement](https://www.moddb.com/games/superfighters-deluxe/addons/gore-improvement-by-eldous12)

![gore improv](https://media.moddb.com/images/downloads/1/317/316623/gorepic.PNG "gore improv")

- Fixes for official clothes
  - Not posted anywhere else as it is not polished enough.
- Le Noir pour Officiele
  - W.i.p

# Used programs
programs used on the making of these items.

## Important
### SFDItemTool
By Liokindy

To import and export .item files:

[MediaFire](https://www.mediafire.com/file/9waf2g6eohm0bjj/SFDItemTool-win64.7z/file) **64 bits windows .exe**

[Mega](https://mega.nz/file/CpB1WIaI#SQ1PgtvzsJEt_qJS265H-odml0udWTXoM3Vg_VIMCgk) **64 bits windows .exe**

Sadly the creator retired it from github. So for now have a mega and mediafire links.

<details>
<summary> Click here for a short setup guide </summary>
  
### Setup.

1. Open `SFDItemTool.exe` ***it will NOT*** open a program but it's necessary so it creates folders on %AppData%
2. The shortcut "SFDItemTool-save-directory" is where the `input` and `output` folders will be. Or you can manually go to `C:\Users\%USERNAME%\AppData\Roaming\SFDItemTool`
3. You put the `.item` files or `.png` folders in the `input` folder depending on what youre going to do. 
4. See below to know what the .bat do

This is what the `.bat` files do:

| .Bat file | Function | Other Notes |
| --- | --- | --- |
| SFDItemTool-folder | Export `.item` into `.png` folders | |
| SFDItemTool-item | Import `.png` folders into `.item` | |
| SFDItemTool-pass | Compress old `.item` files more | Not necessary anymore. |

`SFDItemTool-pass` used to compress `.item` more. But at some point between 1.4 to 1.4.2 development. the compression was implemented officially

</details>

> [!TIP]
>  Go extract first an .item from sfd so you can look at how the formatting is. you can find official sfd items in the root folder at `Superfighters Deluxe\Content\Data\Items`

## Optional

### AnimViewer
By Liokindy

To view animations while being able to modify them in real time:
https://github.com/Liokindy/AnimViewer

---

### Vercel app Item editor 
By NearHuscarl

> [!WARNING]
> Since years it hasn't been working to make items. But its good for visualizing items.

In case you don't know what part belongs to what, or want to quickly test something
https://superfighters.vercel.app/item

---

### LibreSprite (drawing app)

[Web Page](https://libresprite.github.io/#!/)

[Github](https://github.com/LibreSprite/LibreSprite)

Usually a good option as it opens automatically sprites in numerical order. it doesn't add pixels that sfd would hate to read.
> [!IMPORTANT]
> Due to some how this app works. It will always open sfd png images on indexed mode. rembember to change it to rgb color mode. otherwise you wont be able to add colors.

> [!TIP]
> You can bind a key to set images to rgb color mode in the top bar: `Edit>KeyboardSHortcuts>Menus` Search for "rgb" then `Sprite > Color Mode > RGB` option should appear. bind whatever key you want. i recommend space + R
> - You can use [this palette](https://www.mediafire.com/file/ac3gbxg06co6ufn/SFDPALETTE-Colourables_1.ase/file) i created for sfd items.

