# IP Info

## <ins>Install

   `npm install ip-info`

## <ins>Example

```js
const IPInfo = require("ip-info")
const getinfo = new IPInfo.getIPInfo();

getinfo.GetCity("90.90.90.90").then(data => {
    console.log(data)
});
```

<ins>Output
```
>> Paris
```

