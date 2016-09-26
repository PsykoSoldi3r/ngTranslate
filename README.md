# ngTranslate
Simple multi language in an AngularJS application

This repo is for distribution on `npm` only.

## Install

You can install this package either with `npm` only.

### npm

```shell
npm install angular-translate
```

Then add `ngTranslate` as a dependency for your app:

```javascript
angular.module('myApp', ['ngTranslate']);
```

Initialize ngTranslate on run of application

```javascript
$translate.Config({
  default :'en_US',
  languages :[
    'nl_NL'
  ]
});
```

Create folder in the root of of your applicatie with name: languages

You will place your language files inside the language folder. File name format as follow: en_US.lang.json. An example file:
```json
{
    "locale": "en_US",
    "name":"ENG_LANG",
    "words": {
        "APP_TITLE" : "Flight App",
        "HOME_FLIGHTS" : "Flights",
        "HOME_EXERCISES" : "Exercises",
        "HOME_FLYING" : "Flying",
        "HOME_KNOWING" : "Knowing",
        "SETTINGS":"Settings",
        "HOME_PARTNERS":"Partners",
	  	"EN_LANG": "English",
	  	"NL_LANG":"Dutch",
	  	"LANGUAGE":"Language"
    }
}
```
