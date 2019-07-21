### MTPing

```javascript
const mtping = require('@mtproto-org/mtping');

const options = {
  host: 'localhost', // default 'localhost'
  port: 3000 // default :80
  mtproxy_port: 1122 // default :2233
  mtproxy_secret: 'aaaa2222bbbb4444cccc6666dddd8888' // default '11112222333344445555666677778888'
}

mtping(options) // http://host:port => { status: 'ok' }
```



### Copyright
Crafted with <3 by [MTProto.org](https://mtproto.org)

Copyright 2019, MTProto.org Team

*Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:*

*The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.*

*THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.*
