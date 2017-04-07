Get host machine (native) endianness (byte order), like Node's
[`os.endianness`](https://nodejs.org/api/os.html#os_os_endianness)
but portable.

```javascript
const hostEndianness = require('host-endianness');
console.log(hostEndianness); // 'LE' or 'BE'
```
