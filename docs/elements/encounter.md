# Encounter

```xml
<encounter id="45923627-08CB-40FD-A7B2-76DDC2FF1C41" sort="1">
    <name>Example Encounter</name>
    <slug>example-encounter</slug>
    <combatant>
        <label>G1</label>
        <x>450</x>
        <y>400</y>
        <monster ref="/monster/goblin" />
    </combatant>
    <combatant>
        <label>G2</label>
        <x>450</x>
        <y>200</y>
        <monster ref="/monster/goblin" />
    </combatant>
    <combatant>
        <label>G3</label>
        <x>700</x>
        <y>200</y>
        <monster ref="/monster/goblin" />
    </combatant>
    <combatant>
        <label>G4</label>
        <x>600</x>
        <y>150</y>
        <monster ref="/monster/goblin" />
    </combatant>
    <combatant>
        <label>H1</label>
        <x>550</x>
        <y>300</y>
        <monster ref="/monster/hobgoblin" />
    </combatant>
</encounter>
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
| descr  | String | description |
| combatant  | [Combatant](combatant.md) | |