# I will take notes on my reading related to storing data locally from web applications

## Storing Data

HTML5 Storage is a way for web pages to store named key/value pairs locally. This happens in the client web browser. Like cookies, this data stays even when you leave the site. 

When in javascript you should check whether or not the browser can support it using a if else statement. All data regardless of type will be saved into the browser using HTML5 Storage as a string so it will need to be parsed after retrieval. 

```If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.

The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9). Therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports. (If you’ve done this before with other events, you can skip to the end of this section. Trapping the storage event works the same as every other event you’ve ever trapped. If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event, too.) (from the source listed below)
```

[<-Back](README.md)

[Source](http://diveinto.html5doctor.com/storage.html)
