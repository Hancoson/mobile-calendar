# mobile calender

[![GitHub stars](https://img.shields.io/github/stars/Hancoson/mobile-calendar.svg)](https://github.com/Hancoson/mobile-calendar/stargazers)
[![npm version](https://img.shields.io/npm/v/jq-mobile-calendar.svg)](https://www.npmjs.com/package/jq-mobile-calendar)
[![GitHub issues](https://img.shields.io/github/issues/Hancoson/mobile-calendar.svg)](https://github.com/Hancoson/mobile-calendar/issues)
[![GitHub license](https://img.shields.io/github/license/Hancoson/mobile-calendar.svg)](https://github.com/Hancoson/mobile-calendar/blob/master/LICENSE)
[![npm](https://img.shields.io/npm/dt/jq-mobile-calendar.svg)](https://www.npmjs.com/package/jq-mobile-calendar)

> A mobile calender plugin.

> [DEMO>>](http://hancoson.github.io/mobile-calendar/test/index.html)

![demo-images](http://7xtxh3.com1.z0.glb.clouddn.com/github/Jietu20171230-212811@2x.jpg
)

> _Be dependent on `jQuery(Zepto)` and `Iscroll` library._

## API

### How to use

Download `mobile-calendar` folder and include it in your HTML document :

```js
<link href="./mobile-calendar/index.css" rel="stylesheet" type="text/css" />

<script src="./mobile-calendar/index.js"></script>
```


```js
$(document).date();

//or
$(document).date({
    theme:"date",
    fromat: 'yyyy/mm/dd'
});
```

Of course, in your HTML you should add `<div id="datePlugin"></div>`. Or you can refer to my demo: `./test/index.html`


### Parameters 
- `theme`：default `data` , only show date；`datetime` show date and time.
- `fromat`：Style . default `yyyy/mm/dd` and `yyyy/mm/dd hh:ii`. Example：
    - `yyyy-mm-dd` and `yyyy-mm-dd hh:ii`
    - `yyyy年mm月dd日` and `yyyy年mm月dd日 hh时ii分`


## Authors

[Hancoson](https://github.com/Hancoson)

[MIT](https://github.com/Hancoson/mobile-calendar/blob/master/LICENSE)