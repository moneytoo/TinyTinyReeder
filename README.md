## Tiny Tiny Reeder

Tiny Tiny RSS client in HTML/JS.

It is not meant as full featured replacement of Tiny Tiny RSS. Instead it is intended as clean and simple client for quick and light reading on the go.

It works best in Chrome (or as PWA); while it may not work in browsers such as Safari (as this client uses features such as ``pointer events``, ``scroll snap`` etc.).

I'm not sure if this client will ever mature into anything bigger, more feature full and configurable but it works more than fine already for me. I use it everyday as my only RSS reader. (But I have only up to 50 articles a day.)<br>
(I use this project to broaden my knowledge about HTML/CSS/JS as last time I learn about HTML was 15 years ago.)   

### Behavior / limitations:

 - List only shows up to 200 unread articles
 - There is no list of feeds (yet; TODO)
 - Opening article doesn't make it read on server! This is intended behavior. Swipe it away (or press ``X``) to mark it read and remove from list.
 - Works offline (no automatic image caching or support for managing read states; automatic background sync in service worker - investigate)

### Installation

Edit ``URL``, ``USERNAME`` and ``PASSWORD`` in ``index.html``. Copy all the files (ideally) on the same host as Tiny Tiny RSS (to avoid configuring cross domain requests). I use path ``/tt-rss/m/``.

### Screenshots

#### List & detail in portrait

<img src="https://brouken.com/tiny-tiny-reeder/light-portrait-list.jpg" width="320px"></img> <img src="https://brouken.com/tiny-tiny-reeder/light-portrait-detail.jpg" width="320px"></img>

#### Landscape

<img src="https://brouken.com/tiny-tiny-reeder/light-landscape.jpg" height="320px"></img> 

#### List & detail in portrait (dark)

<img src="https://brouken.com/tiny-tiny-reeder/dark-portrait-list.jpg" width="320px"></img> <img src="https://brouken.com/tiny-tiny-reeder/dark-portrait-detail.jpg" width="320px"></img>

#### Landscape (dark)

<img src="https://brouken.com/tiny-tiny-reeder/dark-landscape.jpg" height="320px"></img>

#### Desktop

 <img src="https://brouken.com/tiny-tiny-reeder/dark-desktop.png" width="800px"></img>

### Controls

 - Tap article in the list to open view article content.
 - Swipe article in the list: Green - go to url of the article; Red - mark article as read and remove from the list. 

<img src="https://brouken.com/tiny-tiny-reeder/light-portrait-swipe-open.jpg" width="320px"></img> <img src="https://brouken.com/tiny-tiny-reeder/light-portrait-swipe-mark_read.jpg" width="320px"></img>

#### Keyboard shortcuts

 - ``J``/``K``: Next/previous article
 - ``V``: Go to article URL
 - ``X``: Mark article as read and remove from list
 - ``R``: Reload list/page
 