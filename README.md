# rEFInd-maelstrom

[rEFInd](http://www.rodsbooks.com/refind/) is an easy to use boot manager for UEFI
based systems. This is a clean and minimal theme for it.

## Installation

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/rEFInd-maelstrom/theme.conf` at the end of
    `refind.conf`.

## Background Sizes

If you find the background looks blurry it may be due to the included wallpaper
being an incorrect resolution for your monitor. You can download the [original
high quality wallpaper][wallpaper], resize it as appropriate, and replace the
`background.png`.

You can of course also choose your own background!

## Attribution

> The OS icons were take from [rEFInd-glassy][glassy] which is using icons from [munlik's repository][munlik].
> Background was made by [your's truly][maelstrom].

[glassy]: https://github.com/Pr0cella/rEFInd-glassy#attributions
[munlik]: https://github.com/munlik/refind-theme-regular
[maelstrom]: https://www.newgrounds.com/art/view/patchstep/maelstrom