# Reading Assignment 13

## Why This Matters

Understanding the environment that coding has an impact on is just as important to coding itself. Just because a program developed looks great or works great might not have the whole picture in mind if where and how the site/program exists isn't taken into account as well.

## Questions To Answer

### Why would a developer use local storage for a web application?

It gives the developer the ability to creating an identification of how a user has visited a site so when they return they will find it in the same state and occur quickly because it is there locally. For instance visiting a weather related site and the user has visited the weather for their local area, the browser will refer to that state 'key' to know the weather for their local area needs to be made available immediately.

### What information should not be stored in local storage?

Any type of authentication the website application requires can be overcome by a user with local priviledges to the machine on which the data is stored. Therefore, it's recommended not to store any sensitive information in local storage. There are too many examples of how malicious code which gains local priviledge access commit crimes from stealing propietary information to fraud to worse.

### Local storage can store what type of data? How would you convert it to that type before storing?

Local storage's challenge is it can only store strings in the various keys kept on the client machinne. When an object needs to be stored it must be broken up as string so natively it will not be stored the right way.  This can be worked around with the JSON.stringify() and JSON.parse() methods. These methods return groups of strings as an object when it is sent back to the server.

## Sources Utilized

[Local Storage And How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

[THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS](http://diveinto.html5doctor.com/storage.html)
