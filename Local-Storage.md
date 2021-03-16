# Local Storage

## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

### DIVING IN
persistent local storage is one of the areas where native client applications have held an advantage over web applications.
For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.
These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. 
If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

*Historically, web applications have had none of these luxuries. Cookies were invented early in the webs history, 
and indeed they can be used for persistent local storage of small amounts of data.* 

But they have three potentially dealbreaking downsides:
+ Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over 
+ Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
+ Cookies are limited to about 4 KB of data ” enough to slow down your application (see above), but not enough to be terribly useful

### HTML5 STORAGE
it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually), Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.


## LIMITATIONS IN CURRENT BROWSERS
In talking about the history of local storage hacks using third-party plugins, I made a point of mentioning the limitations of each technique, such as storage limits. I just realized that I havent mentioned anything about the limitations of the now-standardized HTML5 Storage.I will give you the answers first, then explain them. The answers, in order of importance, are megabytes, â€œQUOTA_EXCEEDED_ERR, and no.

## HTML5 STORAGE IN ACTION

Let's see HTML5 Storage in action. Recall the Halma game we constructed in the canvas chapter. Theres a small problem with the game: if you close the browser window mid-game, you will lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves youâ€™ve made, the position of each of the pieces on the board, and even whether a particular piece is selected.

