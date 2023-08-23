![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301007/เครื่องซักผ้าฝาบน/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "120"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301007/เครื่องซักผ้าฝาบน/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301007",
    "model"     : "เครื่องซักผ้าฝาบน",
    "serial"    : "WSH-SN01",
    "name"      : "firmware version",
    "value"     : "150"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301007/เครื่องซักผ้าฝาบน/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301007",
    "model"     : "เครื่องซักผ้าฝาบน",
    "serial"    : "WSH-SN01",
    "name"      : " geo-location", " location placement"
    "value"     : "164"

}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301007/เครื่องซักผ้าฝาบน/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301007",
    "model"     : "เครื่องซักผ้าฝาบน",
    "serial"    : "WSH-SN01",
    "name"      : "geo-location",
    "value"     : "163"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/get/6310301007/เครื่องซักผ้าฝาบน/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301007",
    "model"     : "เครื่องซักผ้าฝาบน",
    "serial"    : "WSH-SN01",
    "name"      : "Monitor-machine-sensor",
    "value"     : "113"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301007/เครื่องซักผ้าฝาบน/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301007",
    "model"     : "เครื่องซักผ้าฝาบน",
    "serial"    : "WSH-SN01",
    "name"      : "status",
}
```
