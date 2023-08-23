![Washing Machine](pictures/iot-machine.png)


## Get hardware level operations e.g. wash_count
Topic: v1cdti/hw/get/6310301007/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "130"
}

## Get firmware version
Topic: v1cdti/hw/get/6310301007/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "get firmware",
    "value"     : "112"
}

## Get manufacture id and geo-location or location placement
Topic: v1cdti/hw/get/6310301007/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "manufacture id",
    "value"     : "A"
}

Payload: {
    "action"    : "get",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "location",
    "value"     : "Uthai"
}

## Set geo-location or location placement
Topic: v1cdti/hw/set/6310301007/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "location",
    "value"     : "Uthai"
}

## Monitor machine sensor
Topic: v1cdti/hw/monitor/6310301007/model-01/WSH-SN001
Payload: {
"action"    : "monitor",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "Vibration Sensor",
    "value"     : "180"
}

## Set machie status to "maint" to indicate this machine need to be maintenance.
Topic: v1cdti/hw/set/6310301007/model-01/WSH-SN001
Payload: {
"action"    : "set",
    "project"   : "6310301007",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "status",
    "value"     : "main"
}
