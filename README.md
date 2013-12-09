
FEDme
=====

A web-service for Nature FED images. http://fedme.rowanmanning.com/

**Current Version:** *0.0.0*  
**Node Support:** *0.10*


Adding FEDs
-----------

Add FED image URLs to [`fedme.js`](fedme.js) at the end of the `things` array. Each FED should be a string containing only the URL, like this:

```
"http://i.imgur.com/Tfq7Bi7.gif"
```


Running
-------

Install [Node.js][node], clone this repo, and run `npm install`. Now you can run the app with Foreman:

```sh
$ foreman start
```

Or by using the command:

```sh
$ ./node_modules/.bin/thingme ./fedme.js
```


License
-------

FEDme is licensed under the [MIT][mit] license.



[mit]: http://opensource.org/licenses/mit-license.php
[node]: http://nodejs.org/
