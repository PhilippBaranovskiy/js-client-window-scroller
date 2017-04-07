# js-client-window-scroller

It uses delayed window.resize listener (with setTimeout).
Bind your listeners to the only one delayed-"resize" event instead of copying that code.

__Add your listener (and get an ID key):__
```
/*
 *    force: true/false, to run your callback right now after adding to the queue.
 */
var callbackID = windowScroller.queue.add( yourFunc, force );
```



__Remove your listener by ID key (and get boolean result):__
```
var removedORnot = windowScroller.queue.remove( callbackID );
```
