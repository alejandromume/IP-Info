# IP Info 3

## <ins>Description
* A simple package for get a lot of info about a IP address
## <ins>Install

   `npm install ip-info3`

## <ins>Modules
* `GetAll() -> Get all the info`
* `GetAS() -> Get the IP AS`
* `GetCity() -> Get the IP City`
* `GetCountry() -> Get the IP Country`
* `GetCountryCode() -> Get the IP Country code`
* `GetISP() -> Get the IP ISP`
* `GetOrg() -> Get the IP Organization`
* `GetRegion() -> Get the IP Region`
* `GetRegionName() -> Get the IP Region name`
* `GetQueryStatus() -> Get if the query was successfull`
* `GetTimezone() -> Get the IP Timezone`
* `GetZip() -> Get the IP zip`

## <ins>Examples

```js
const IPInfo = require("ip-info3")
const getinfo = new IPInfo.getIPInfo();

getinfo.GetCity("90.90.90.90").then(data => {
    console.log(data)
});
```

<ins>Output
```
>> Paris
```

---
```js
const IPInfo = require("ip-info3")
const getinfo = new IPInfo.getIPInfo();

getinfo.GetRegionName("90.90.90.90").then(data => {
    console.log(data)
});
```

<ins>Output
```
>> Île-de-France
```


