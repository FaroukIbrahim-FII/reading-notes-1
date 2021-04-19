# Read: 13 - Local Storage

#### DIVING IN : Persistent local storage is one of the areas where native client applications have held an advantage over web applications. you can embed your own database, invent your own file format.

#### Cookies have three potentially dealbreaking downsides :
* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet .
* Cookies are limited to about 4 KB of data — enough to slow down your application.

#### The problem that HTML5 set out to solve: to provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.

### Check for HTML5 Storage :

```JAVASCRIPT
    function supports_html5_storage() {
        try {
            return 'localStorage' in window && window['localStorage'] !== null;
        } catch (e) {
            return false;
        }
    }

    // ***************

    if (Modernizr.localstorage) {
         // window.localStorage is available!
    } else {
        // no native support for HTML5 storage :(
        // maybe try dojox.storage or a third-party solution
    }
```

#### HTML5 Storage is based on named key and value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string.

#### If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever `setItem()`, `removeItem()`, or `clear()` is called and actually changes something. 

#### with HTML5 Storage, we can save the progress locally, within the browser itself. For the purpose of games, programs, or even anything that you may think of, it is very useful and saves the burden of burden on the many quartzes and the large number of storage in databases.


[ Back To README !]( https://yousefabujalboush.github.io/reading-notes/ )