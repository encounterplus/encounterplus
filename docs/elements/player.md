# Player

```xml
<player id="79A826C2-1694-4EEA-92FB-70B0F511BCDD">
    <name>Thorin Stoneheart</name>
    <slug>thorin-stoneheart</slug>
    <race>Dwarf</race>
    <class>Fighter</class>
    <level>1</level>
    <xp>0</xp>
    <ac>17</ac>
    <hp>12</hp>
    <speed>30 feet</speed>
    <str>16</str>
    <dex>9</dex>
    <con>15</con>
    <int>11</int>
    <wis>13</wis>
    <cha>14</cha>
    <descr></descr>
    <party></party>
    <faction></faction>
    <light id="D9F3DCF9-BE84-49F6-BE41-92E564EE7B6B">
        <enabled>YES</enabled>
        <radiusMin>20</radiusMin>
        <radiusMax>40</radiusMax>
        <color>#ffffff</color>
        <opacity>0.5</opacity>
        <alwaysVisible>NO</alwaysVisible>
    </light>
</player>
```

## Attributes

| Attribute | Type | Description |
| --------- | ---- | ----------- |
| id  | String  | UUIDv4 |

## Fields

| Field  | Type | Description |
| ------ | ---- | ----------- |
| name  | String | |
| slug  | String | for referencing |
| race  | String |  |
| class  | String | Artificer, Barbarian, Bard, Cleric, Druid, Fighter, Monk, Paladin, Ranger, Rogue, Sorcerer, Warlock, Wizard |
| level  | Integer |  |
| xp  | Integer |  |
| ac | String | 14 (hide armor) or 14 |
| hp | Integer | 11 |
| speed | String |  |
| str | Integer |  |
| dex | Integer |  |
| con | Integer |  |
| int | Integer |  |
| wis | Integer |  |
| cha | Integer |  |
| descr | String | description |
| party | String (Deprecated) | |
| skill | String | Skills |
| senses | String |  |
| passive | Integer | Passive Perception |
| initiative | Integer | Initiative Modifier |
| spells | String | Fireball, Firestorm |
| equipment | String | Staff of Fireball, Adamantine Armor |
| ideals | String |  |
| bonds | String |  |
| flaws | String |  |
| ddb | String | Link to DDB character sheet |
| image | String | art image filename |
| token | String | token image filename |
| bookmark | Boolean | YES, NO |
| light | [Light](light.md) |  |