# Light

```XML
<light id="FC91A4BD-7022-4508-A58A-5CBF11267B49">
    <enabled>YES</enabled>
    <radiusMin>20</radiusMin>
    <radiusMax>40</radiusMax>
    <color>#ff8000</color>
    <opacity>0.5</opacity>
    <alwaysVisible>NO</alwaysVisible>
</light>
```

## Attributes

| Attribute | Type | Description |
| --------- | ---- | ----------- |
| id  | String  | UUIDv4 |

## Fields

| Field  | Type | Description |
| ------ | ---- | ----------- |
| enabled  | Boolean | YES, NO |
| radiusMin  | Integer | bright light radius, in ft |
| radiusMax  | Integer | dim light radius, in ft |
| color | String | HEX format, #CCCCCC |
| opacity | Float | 0.0 - 1.0 |
| alwaysVisible  | Boolean | YES, NO, always visible from player perspective, even if there is no line of sight. Set to NO for standard objects like torches, fires, etc.. |