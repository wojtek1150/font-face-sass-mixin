## Font face mixin

```
@mixin font-face($name, $path, $exts, $local, $local-slug, $weight, $style)
```

## Params
```
$name (string) - Font family name used in page (required)
$path (string) - path to font family (required)
$exts (array) - extensions to add (required)
$local (string) - local font family name (on your pc) (optional)
$local-slug (string) - local font family name slug (optional)
$weight (string) - font family weight, default 400 (optional)
$style (string) - font family style, default normal (optional)
```

## DEMO / USAGE
```
@include font-face("Open Sans", "../fonts/OpenSans-Regular", woff2 woff, "Open Sans", "OpenSans");
@include font-face("Open Sans", "../fonts/OpenSans-Bold", woff2 woff, "Open Sans Bold", "OpenSans-Bold", 700, normal);
```
