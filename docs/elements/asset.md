# Asset

```xml
<asset id="445D1DF0-745E-44D6-9EF0-69F67D45B277">
    <name>Campfire</name>
    <type>image</type>
    <resource>Campfire.png</resource>
</asset>
```

## Attributes

| Attribute | Type | Description |
| --------- | ---- | ----------- |
| id  | String  | UUIDv4 |
| parent  | String  | UUID of parent item |
| sort  | String  | for sorting |

## Fields

| Field  | Type | Description |
| ------ | ---- | ----------- |
| name  | String | |
| slug  | String | for referencing |
| type  | String | image, pattern, spriteSheet |
| tags  | String | |
| resource  | String | resource filename |
| size  | String | logical grid size, [w]x[h], example: 1x2 |
| frameWidth  | Integer | single frame width in spritesheet |
| frameHeight  | Integer | single frame height in spritesheet |
| duration  | Float | animation duration in spritesheet |
| scale  | Float | pattern scale  |
| gridAlign  | Boolean | YES, NO, pattern size grid align |
