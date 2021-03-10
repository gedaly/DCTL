# Davinci CTLs For Fun & Profit

Want to add a couple fun features to Blackmagic Design's DaVinci Resolve? These are just my experiments, so use at your own risk. More coming soon. [Lemme know what you think!](https://twitter.com/gedaly)

## Installation

Add the .dctl files to your Resolve LUT folder, or a sub-folder to keep them organized.

### Mac

` /Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT `

### Windows

` C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT `

### Linux

` /home/resolve/LUT `

## Contents

### filmic_log3.dtcl

If you like shooting footage with your iphone, you should be using [Filmic Pro](https://www.filmicpro.com/). It's a great app for controlling your image, and it allows you to record in 10 bit and LOG. They have a LUT on their website, but it super saturates colors in a way that doesn't leave me with the control I want.

## About DCTLs

A DCTL lives somewhere between a LUT and a Plugin. It's Resolve's way of giving users the ability to add mathematical transforms or create custom controls.

### Further Reading + Resources

* https://github.com/ampas/CTL
* https://github.com/baldavenger/DCTLs
* Resolve Developer Documentation:
    * Mac: ` /Library/Application Support/Blackmagic Design/Davinci Resolve/Developer/DaVinciCTL `
    * Windows: ` C:/ProgramData/Blackmagic Design/DaVinci Resolve/Support/Developer/DaVinciCTL `
    * Linux: ` /opt/resolve/Developer/DaVinciCTL `
