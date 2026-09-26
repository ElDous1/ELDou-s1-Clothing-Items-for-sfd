
items i made, both their decompiled png versions and .item versions.

# Used programs
programs used on the making of these items.

## Important
### SFDItemTool
By Liokindy

To import and export .item files:

[MediaFire](https://www.mediafire.com/file/9waf2g6eohm0bjj/SFDItemTool-win64.7z/file) **64 bits windows .exe**

[Mega](https://mega.nz/file/CpB1WIaI#SQ1PgtvzsJEt_qJS265H-odml0udWTXoM3Vg_VIMCgk) **64 bits windows .exe**

Sadly the creator retired it from github. so for now have a mega and mediafire links.
*Setup.*
1. open the .exe, ***it will NOT*** open a program but its necessary so it creates folders on %AppData%
2. the shortcut "SFDItemTool-save-directory" is where the input and output folders will be. otherwise go to `C:\Users\%USERNAME%\AppData\Roaming\SFDItemTool`
This is what the .bat files do:

| .Bat file | Function | Other Notes |
| --- | --- | --- |
| SFDItemTool-folder | Export `.item` into `.png` folders | |
| SFDItemTool-item | Import `.png` folders into `.item` | |
| SFDItemTool-pass | Compress old `.item` files more | Not necessary anymore. |

`SFDItemTool-pass` used to compress `.item` more but at some point between 1.4 to 1.4.2 development. the compression was implemented officially.

## Optional

### AnimViewer
To view animations while being able to modify them in real time:
https://github.com/Liokindy/AnimViewer

### Vercel app Item editor 
> [!WARNING]
> Since years it hasn't been working to make items. But its good for visualizing items.

In case you don't know what part belongs to what, or want to quickly test something
https://superfighters.vercel.app/item

### LibreSprite

[Web Page](https://libresprite.github.io/#!/)
[Github](https://github.com/LibreSprite/LibreSprite)
Usually a good option as it opens automatically sprites in numerical order. it doesnt add pixels that sfd would hate to read.
> [!IMPORTANT]
> Due to some how this app works. It will always open sfd png images on indexed mode. rembember to change it to rgb color mode. otherwise you wont be able to add colors.

> [!TIP]
> You can bind a key to set to rgb color mode in the top bar: `Edit>KeyboardSHortcuts>Menus` Search for "rgb" then `Sprite > Color Mode > RGB` option should appear. bind whatever key you want. i recommend space + R
> - You can use [this palette](https://www.mediafire.com/file/ac3gbxg06co6ufn/SFDPALETTE-Colourables_1.ase/file) i created for sfd items.

