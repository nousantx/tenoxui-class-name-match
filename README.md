# TenoxUI Class Name Matcher

TenoxUI use regexp for match all possible class from element, it will get the classname's prefixes (type) and its values like this :

```js
{type}-{value}
```

And yeah, this is the function for handles all the possible classes before applying the styles. See the example from [tenoxui code](https://github.com/tenoxui/css/blob/22fd1946e02e529054437f0e32ab54c17640ad0a/src/ts/tenoxui.ts#L205).
