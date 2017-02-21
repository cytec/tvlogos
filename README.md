# tvlogos
collection of mostly german tv channel logos


# How to Contribute

1. fork this repo
2. download the channel logo you want to add from wikipedia
3. convert the logo to 236x236px PNG with transparent background
4. naming should follow the networks name all lowercase spaces should be replaced with a dash (`-`)

conversion with imagemagick:

`convert IMAGE -resize 236x236 -gravity center -background transparent -extent 236x236 IMAGE`


### Example:
Given you want to add the logo from TNT Serie:

1. Download the image from https://de.wikipedia.org/wiki/TNT_Serie
2. convert it `convert TNT_Serie_Logo_2016.png -resize 236x236 -gravity center -background transparent -extent 236x236 TNT_Serie_Logo_2016.png`
3. rename it to `tnt-serie.png`
4. create a PR
