# Monster

```XML
<monster id="6D875315-4ABC-45E2-B77E-031493092136">
    <name>Aboleth</name>
    <slug>aboleth</slug>
    <size>L</size>
    <type>aberration</type>
    <alignment>lawful evil</alignment>
    <ac>17</ac>
    <hp>135 (18d10+36)</hp>
    <speed>10 ft., swim 40 ft.</speed>
    <str>21</str>
    <dex>9</dex>
    <con>15</con>
    <int>18</int>
    <wis>15</wis>
    <cha>18</cha>
    <role>enemy</role>
    <save>Con +6 Int +8 Wis +6</save>
    <skill>History +12 Perception +10</skill>
    <senses>darkvision 120 ft., passive Perception 20</senses>
    <passive>20</passive>
    <languages>Deep Speech, telepathy 120 ft.</languages>
    <cr>10</cr>
    <save>Con +6 Int +8 Wis +6</save>
    <environment>underdark</environment>
    <trait>
        <name>Amphibious</name>
        <text>The aboleth can breathe air and water.</text>
    </trait>
    <trait>
        <name>Mucous Cloud</name>
        <text>While underwater, the aboleth is surrounded by transformative mucus. A creature that touches the aboleth or that hits it with a melee attack while within 5 ft. of it must make a DC 14 Constitution saving throw. On a failure, the creature is diseased for 1d4 hours. The diseased creature can breathe only underwater.</text>
    </trait>
    <trait>
        <name>Probing Telepathy</name>
        <text>If a creature communicates telepathically with the aboleth, the aboleth learns the creature&apos;s greatest desires if the aboleth can see the creature.</text>
    </trait>
    <action>
        <name>Multiattack</name>
        <text>The aboleth makes three tentacle attacks.</text>
    </action>
    <action>
        <name>Tentacle</name>
        <text>Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 12 (2d6 + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or become diseased. The disease has no effect for 1 minute and can be removed by any magic that cures disease. After 1 minute, the diseased creature&apos;s skin becomes translucent and slimy, the creature can&apos;t regain hit points unless it is underwater, and the disease can be removed only by heal or another disease-curing spell of 6th level or higher. When the creature is outside a body of water, it takes 6 (1d12) acid damage every 10 minutes unless moisture is applied to the skin before 10 minutes have passed.</text>
    </action>
    <action>
        <name>Tail</name>
        <text>Melee Weapon Attack: +9 to hit, reach 10 ft. one target. Hit: 15 (3d6 + 5) bludgeoning damage.</text>
    </action>
    <action>
        <name>Enslave (3/day)</name>
        <text>The aboleth targets one creature it can see within 30 ft. of it. The target must succeed on a DC 14 Wisdom saving throw or be magically charmed by the aboleth until the aboleth dies or until it is on a different plane of existence from the target. The charmed target is under the aboleth&apos;s control and can&apos;t take reactions, and the aboleth and the target can communicate telepathically with each other over any distance.
Whenever the charmed target takes damage, the target can repeat the saving throw. On a success, the effect ends. No more than once every 24 hours, the target can also repeat the saving throw when it is at least 1 mile away from the aboleth.</text>
    </action>
    <legendary>
        <name>Detect</name>
        <text>The aboleth makes a Wisdom (Perception) check.</text>
    </legendary>
    <legendary>
        <name>Tail Swipe</name>
        <text>The aboleth makes one tail attack.</text>
    </legendary>
    <legendary>
        <name>Psychic Drain (Costs 2 Actions)</name>
        <text>One creature charmed by the aboleth takes 10 (3d6) psychic damage, and the aboleth regains hit points equal to the damage the creature takes.</text>
    </legendary>
</monster>
```

## Attributes

| Attribute | Type | Description |
| --------- | ---- | ----------- |
| id  | String  | UUIDv4 |

## Fields

| Field  | Type | Description |
| ------ | ---- | ----------- |
