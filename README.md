bootstrap-popover-move
======================

Based on popover of bootstrap, but has mouseFollow, that allow the popover to follow the mouse movement.

``` javascript

$('.popover-area').popover({
	placement: 'auto left'
    container: 'body',
    mouseOffset: 20,
    followMouse: true,
    trigger: 'hover'
});

```

The conditions to use to movement are: 

* trigger on ```hover``` 
* keep a ```auto``` placement.
* container needs to be ```body```

Also, the project allow the use of map  ```area``` as a selector to popover, with the follow code:

``` javascript

$('area').popover({
    measure: 'img.image-map',
    mouseOffset: 20,
    container: 'body',
    followMouse: true
});

```

The conditions to use on area map are:

* give the image reference as ```measure``` options
* followMouse and his conditions above