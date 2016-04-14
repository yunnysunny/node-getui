The GeTui Server SDK
------------------------

[Ge Tui](http://http://www.getui.com/)

The server SDK is a wrapper of all the http/https API calls, which could be found [here](http://docs.getui.com/pages/viewpage.action?pageId=589866)


## Install

```bash
$ npm install getui
```

## Init

```js
var GeTui = require( 'getui' );
var api = new GeTui('HOST', 'APPKEY', 'MASTERSECRET');
```

The `HOST` can be `http://sdk.open.api.igexin.com/apiex.htm` or `https://api.getui.com/apiex.htm`.



## License
[MIT](LICENSE)