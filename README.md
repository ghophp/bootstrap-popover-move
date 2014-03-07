bootstrap-popover-move
======================

Based on popover of bootstrap, but has placement mouse, that allow the mouse to follow the mouse movement

``` javascript

$('.popover-area').popover({
	placement: 'auto left'
    mouseOffset: 20,
    followMouse: true,
    trigger: 'hover'
});

```

The conditions to use to movement is, trigger on ```hover``` and keep a ```auto``` placement.