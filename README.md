<<<<<<< HEAD
# MyVoix JS

A JavaScript library to use voice command in Chrome.
This Library is not only wrap google's API, but also supply a smart learning feature which enables the browser to learn user's pronounce

### Standalone
You can use the standalone version:
```html
<script src="myvoix.js"></script>
```

## How-to
Create a new instance of Voix.
```js
var _myVoix = new MyVoix(undefined,undefined,true);
```

## API
### Voix(lang)
Create a new instance of `Voix`.

***Args***

- `pConfig`: refer to webkitSpeechRecognition's config.

- `pCommands`: A serious of commands which have been stored before.

- `pIsLoop`: whether to keep detecting.

***eg:***

```
var MyVoix=function(pConfig,pCommands,pIsLoop);
```


### bind(pCommand, pListener)

***Args***

- `pCommand`: a string or an array of string

- `pListener`: the function which will be triggered

***eg:***

bind a string

`_myVoix.bind('go',function(){});`

bind an array

`_myVoix.bind(['go','start'],function(){});`

### unbind(pCommand, pListener)

***Args***

- `pCommand`: a string or an array of string

- `pListener`: the function need to be unbund

***eg:***

refer to **bind**

### createSoundWave()

***Args***

- `opt`: the config of soundwave

***eg:***
				
    _myVoix.createSoundWave({
    	canvas:document.getElementById('myCanvas'),
    	height:600,
    	width:800,
    	noise:0.01,
    	F:2
    });

## Maintained by
- E-mail: ArthusLiang@gmail.com

## License
Licensed under the MIT license.

Copyright (c) 2014 yulianghuang
=======
MyVoix
======

Libaray to use voice command for html5
>>>>>>> dd17d84e9869081ab05e7b80a3ff706989e2dc2c
