# request.js
> Probably the most lightweight / simple Javscript request library.

## why?
> It does one thing and it does it well.

## Usage:

        //request(<endpoint>, <type>, <data>, <callback_function>)

        request("/api/registeruser", 'PUT', {"name": "John"}, function(data) {
            console.log(data);
        });

## Install using npm
> [https://www.npmjs.com/package/request-tiny](https://www.npmjs.com/package/request-tiny)

    npm install request-tiny
