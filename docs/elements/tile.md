# Tile

```XML
<tile id="D22B242D-0F74-4D62-BCF0-AB834B1CF81E">
    <x>322</x>
    <y>574</y>
    <width>94</width>
    <height>98</height>
    <rotation>0</rotation>
    <opacity>1.0</opacity>
    <layer>token</layer>
    <zIndex>0</zIndex>
    <hidden>NO</hidden>
    <locked>NO</locked>
    <asset id="445D1DF0-745E-44D6-9EF0-69F67D45B277">
        <name>Campfire</name>
        <type>image</type>
        <resource>Campfire.png</resource>
    </asset>
    <component>
        <type>filter.tint</type>
        <enabled>YES</enabled>
        <color>#00ff00</color>
    </component>
    <light id="FC91A4BD-7022-4508-A58A-5CBF11267B49">
        <enabled>YES</enabled>
        <radiusMin>20</radiusMin>
        <radiusMax>40</radiusMax>
        <color>#ff8000</color>
        <opacity>0.5</opacity>
        <alwaysVisible>NO</alwaysVisible>
    </light>
</tile>
```

## Attributes

| Attribute | Type | Description |
| --------- | ---- | ----------- |
| id  | String  | UUIDv4 |

## Fields

| Field  | Type | Description |
| ------ | ---- | ----------- |
| x | Integer | position |
| y | Integer | position |
| width | Integer |  |
| height | Integer |  |
| roatation | Integer | 0 - 360, in degrees |
| opacity | Float | 0.0 - 1.0 |
| zIndex | Integer | z-order |
| hidden  | Boolean | YES, NO |
| locked  | Boolean | YES, NO |
| asset  | [Asset](asset.md) | associated asset |
| light  | [Light](light.md) | light/vision config |
| comopnent  | [Component](component.md) | additional functionalities |