# 对象定义
```
deviceInfo
{
     "did":"",
     "pid":"",
     "parentID":"",
     "mac":"",
     "name":"",
     "cookie":""
}
```
```
devicePairedInfo
{
     "did":"",
     "pid":"",
     "mac":"",
     "cookie":""
}
```

```
endpoint
{
    "endpointId": "appliance-001",
    "friendlyName": "卧室灯",
    "isReachable":true,
    "description": "由BroadLink生产的灯",
    "manufacturerName": "Sample Manufacturer",
    "icon":"产品图片URL",
    "brand":"品牌",
    "displayCategories": [
        "LIGHT"
    ],
    "cookie": {
        "extraDetail1": "某些设备可能会用到这个cookie，需要在控制时原样返回",
        "extraDetail2": "某些设备可能会用到这个cookie，需要在控制时原样返回",
        "extraDetail3": "某些设备可能会用到这个cookie，需要在控制时原样返回",
        "extraDetail4": "某些设备可能会用到这个cookie，需要在控制时原样返回"
    },
    "capabilities": [
        {
            "type": "DNAInterface",
            "interface": "DNA.PowerControl",
            "version": "2",
            "properties": {
                "supported": [
                    {
                        "name": "powerState"
                    }
                ],
                "proactivelyReported": true,
                "retrievable": true
            },
           "actions": {
               "supported": [
                {
                     "name": "ChangePowerState"
                }
               ]
           }
        }
```
