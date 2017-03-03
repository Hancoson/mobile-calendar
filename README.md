# mobile calender(移动端日期选择插件)

> [DEMO>>](http://hancoson.github.io/mobile_calendar/index.html)

> _依赖 `jQuery(Zepto)`、`Iscroll`第三方库._

## API说明

### 调用

```
$(document).date();

//or
$(document).date({
    theme:"date",
    fromat: 'yyyy/mm/dd'
});
```

### 参数说明
- `theme`：主题。默认`data`，只显示日期；`datetime`显示日期和时间
- `fromat`：风格。默认`yyyy/mm/dd`和`yyyy/mm/dd hh:ii`。支持：
    - `yyyy-mm-dd`和`yyyy-mm-dd hh:ii`
    - `yyyy年mm月dd日`和`yyyy年mm月dd日 hh时ii分`

