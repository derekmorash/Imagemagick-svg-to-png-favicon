Imagemagick commands for creating all necessary icons for the web from an svg file.

```
convert -density 400 logo.svg -transparent white -gravity center -resize 57x57 apple-touch-icon-57x57.png
convert -density 400 logo.svg -transparent white -gravity center -resize 60x60 apple-touch-icon-60x60.png
convert -density 400 logo.svg -transparent white -gravity center -resize 72x72 apple-touch-icon-72x72.png
convert -density 400 logo.svg -transparent white -gravity center -resize 76x76 apple-touch-icon-76x76.png
convert -density 400 logo.svg -transparent white -gravity center -resize 114x114 apple-touch-icon-114x114.png
convert -density 400 logo.svg -transparent white -gravity center -resize 120x120 apple-touch-icon-120x120.png
convert -density 400 logo.svg -transparent white -gravity center -resize 144x144 apple-touch-icon-144x144.png
convert -density 400 logo.svg -transparent white -gravity center -resize 152x152 apple-touch-icon-152x152.png
convert -density 400 logo.svg -transparent white -gravity center -resize 16x16 favicon-16x16.png
convert -density 400 logo.svg -transparent white -gravity center -resize 32x32 favicon-32x32.png
convert -density 400 logo.svg -transparent white -gravity center -resize 96x96 favicon-96x96.png
convert -density 400 logo.svg -transparent white -gravity center -resize 128 favicon-128.png
convert -density 400 logo.svg -transparent white -gravity center -resize 196x196 favicon-196x196.png
convert -density 400 logo.svg -transparent white -gravity center -resize 64x64 favicon.ico
convert -density 400 logo.svg -transparent white -gravity center -resize 70x70 mstile-70x70.png
convert -density 400 logo.svg -transparent white -gravity center -resize 144x144 mstile-144x144.png
convert -density 400 logo.svg -transparent white -gravity center -resize 150x150 mstile-150x150.png
convert -density 400 logo.svg -resize 140x140 -gravity center -extent 310x150 -transparent white mstile-310x150.png
convert -density 400 logo.svg -transparent white -gravity center -resize 310x310 mstile-310x310.png
```

Add icons to your page.

```html
<link rel="apple-touch-icon-precomposed" sizes="57x57" href="apple-touch-icon-57x57.png" />
<link rel="apple-touch-icon-precomposed" sizes="114x114" href="apple-touch-icon-114x114.png" />
<link rel="apple-touch-icon-precomposed" sizes="72x72" href="apple-touch-icon-72x72.png" />
<link rel="apple-touch-icon-precomposed" sizes="144x144" href="apple-touch-icon-144x144.png" />
<link rel="apple-touch-icon-precomposed" sizes="60x60" href="apple-touch-icon-60x60.png" />
<link rel="apple-touch-icon-precomposed" sizes="120x120" href="apple-touch-icon-120x120.png" />
<link rel="apple-touch-icon-precomposed" sizes="76x76" href="apple-touch-icon-76x76.png" />
<link rel="apple-touch-icon-precomposed" sizes="152x152" href="apple-touch-icon-152x152.png" />
<link rel="icon" type="image/png" href="favicon-196x196.png" sizes="196x196" />
<link rel="icon" type="image/png" href="favicon-96x96.png" sizes="96x96" />
<link rel="icon" type="image/png" href="favicon-32x32.png" sizes="32x32" />
<link rel="icon" type="image/png" href="favicon-16x16.png" sizes="16x16" />
<link rel="icon" type="image/png" href="favicon-128.png" sizes="128x128" />
<meta name="application-name" content="Site Name"/>
<meta name="msapplication-TileColor" content="#FFFFFF" />
<meta name="msapplication-TileImage" content="mstile-144x144.png" />
<meta name="msapplication-square70x70logo" content="mstile-70x70.png" />
<meta name="msapplication-square150x150logo" content="mstile-150x150.png" />
<meta name="msapplication-wide310x150logo" content="mstile-310x150.png" />
<meta name="msapplication-square310x310logo" content="mstile-310x310.png" />
```

Might make this a script someday.