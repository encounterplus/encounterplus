# Module

```xml
<module id="AA9B0CA6-E75D-4781-8CA8-CA1DE5B88AB0">
	<name>Examples</name>
	<description>Few examples for future reference.</description>
	<slug>examples</slug>
	<author>EncounterPlus</author>
	<code>EX01</code>
	<category>other</category>
	<image>cover_1Sez3L.jpg</image>
	<page id="2BA4481B-B606-4084-9AF6-7DC70AB88A05">
		<name>Example Page</name>
		<slug>example-page</slug>
		<content>&lt;p&gt;&lt;img src=&quot;heading.png&quot; alt=&quot;heading&quot; class=&quot;size-cover&quot;&gt;&lt;/p&gt;
        &lt;h1 id=&quot;heading-1&quot;&gt;Heading 1&lt;/h1&gt;
        &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Massa tempor nec feugiat nisl pretium fusce id. Tincidunt augue interdum velit euismod. Odio pellentesque diam volutpat commodo sed egestas. Mattis molestie a iaculis at erat. Nibh venenatis cras sed felis. Dignissim enim sit amet venenatis urna cursus eget nunc scelerisque.&lt;/p&gt;
  </content>
	</page>
	<map id="038C45F6-5DD4-480C-B2D0-C7675746EA48" sort="2">
		<name>Example Map</name>
		<description></description>
		<gridSize>50</gridSize>
		<gridOffsetX>0</gridOffsetX>
		<gridOffsetY>0</gridOffsetY>
		<gridColor>#cccccc</gridColor>
		<gridVisible>YES</gridVisible>
		<scale>1.0</scale>
		<fogVisible>NO</fogVisible>
		<lineOfSight>YES</lineOfSight>
		<daylight>0.0</daylight>
		<image>example-map_LD3xsa.jpg</image>
		<video></video>
		<canvas>example-map-canvas_038C45.svg</canvas>
		<snapshot>example-map-snapshot_MnJlPN.jpg</snapshot>
		<fog></fog>
		<floor></floor>
		<marker>
			<name>Example Page</name>
			<color>#268bd2</color>
			<shape>pin</shape>
			<size>medium</size>
			<hidden>YES</hidden>
			<locked>NO</locked>
			<x>734</x>
			<y>547</y>
			<content ref="/page/example-page" />
		</marker>
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
			<light id="FC91A4BD-7022-4508-A58A-5CBF11267B49">
				<enabled>YES</enabled>
				<radiusMin>20</radiusMin>
				<radiusMax>40</radiusMax>
				<color>#ff8000</color>
				<opacity>0.5</opacity>
				<alwaysVisible>NO</alwaysVisible>
			</light>
		</tile>
	</map>
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
			<label>H1</label>
			<x>550</x>
			<y>300</y>
			<monster ref="/monster/hobgoblin" />
		</combatant>
	</encounter>
</module>
```

## Attributes

| Attribute | Type | Description |
| --------- | ---- | ----------- |
| id  | String  | UUIDv4 |
| sort  | String  | for sorting |
| version  | String  |  |

## Fields

| Field  | Type | Description |
| ------ | ---- | ----------- |
| name  | String | |
| slug  | String | for referencing |
| description  | String | |
| author  | String |  |
| code  | String |  |
| category  | String | adventure, other |
| image | String | cover image filename |
| bookmark | Boolean | YES, NO|
| map | [Map](map.md) |  |
| page | [Page](page.md) |  |
| encounter | [Encounter](encounter.md) |  |
| group | [Group](group.md) |  |


