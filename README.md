# mColorPicker

jQuery color picker plugin. 

## Installing

After jQuery is loaded.
```
<script type="text/javascript" src="javascripts/mColorPicker.js"></script>
```
Then set any inits listed below.

## Usage

To turn of automatic operation and run manually set:
```
$.fn.mColorPicker.init.replace = false
```
To use manually call like any other jQuery plugin
```
$('input.foo').mColorPicker({options})
```

### Options
Option | Default | Notes
--- | --- | ---
imageFolder | 'images/' | *Change to move image location*
swatches | ["#ffffff", "#ffff00", "#00ff00", "#00ffff", "#0000ff", "#ff00ff", "#ff0000", "#4c2b11", "#3b3b3b", "#000000"] | *Initial colors in the swatch, must be an array of 10 colors*


### Inits
Init | Default | Notes
--- | --- | ---
replace | '[type=color]' | *Selector to use to decide which DOM objects to automatically turn into to a color picker*
enhancedSwatches | true | *Set to false to turn off saving and loading of swatch to cookies*
allowTransparency | true | *Set to false to turn off transperancy as a color option*
showLogo | true | *Set to false to turn off the meta100 logo*

## Authors

* **Will Shostak** - *Initial work* - [GitLab](https://github.com/wshostak)
