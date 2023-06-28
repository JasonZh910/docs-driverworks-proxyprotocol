## RINGER\_VOLUME\_CHANGED

This notification is issued by the proxy when the endpoint’s Monitor Mode setting has changed. 


### Signature

`RINGER_VOLUME_CHANGED ()`


| Parameter | Description |
| --- | --- |
| int | The proxy device id of the intercom endpoint whose device state information is being returned |
| ringerVol | Numeric value indicating the current value of this setting. (0 to 100) |


### Example

```lua
<device_state proxyid =[10]>
    <ringerVoL>[0]</ringerVoL>
</device_state>
```

