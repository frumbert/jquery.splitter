# jQuery Splitter

jQuery Splitter is plugin that split your content with movable splitter between them. Touch friendly.

### Notable differences from original source

- renamed to splitr to avoid possible confusion with array `.split()`
- added methods
- added locked option

# Example

```javascript
$('#foo').splitr({
    orientation: 'horizontal',
    limit: 10,
    position: '50%' // if there is no percentage it interpret it as pixels
});
```

# Settable options

`limit`: pixel amount as minimum size
`position`: number or pixel value representing position from top/left
`orientation`: 'horizontal' or 'vertical'
`locked`: whether splitter is draggble
`invisible`: whether the splitter bar is visible
`onDrag`: function executed whilst dragging
`onDragStart`: function executed when dragging begins
`onDragEnd`: function executed when dragging finishes

# Methods

Called like this `$inst.splitr("refresh")`.

`"refresh"`: cause the current splitter to re-paint
`"size",n`: sets the current position from top/left (px or %) to `n`
`"lock"`: locks the splitter
`"unlock"`: unlocks the splitter
`"destroy"`: removes the splitter, events, and leaves everything "as is"

# Demo (original fork)

<http://jquery.jcubic.pl/splitter.php>

# Patch Contributors

* Robert Tupelo-Schneck
* Taras Strypko
* [Yury Plashenkov](https://github.com/plashenkov)
* Tim St.Clair (https://github.com/frumbert)

# License

Copyright (C) 2010-2013 Jakub Jankiewicz &lt;<http://jcubic.pl>&gt;

Released under the terms of the [GNU Lesser General Public License](http://www.gnu.org/licenses/lgpl.html)
