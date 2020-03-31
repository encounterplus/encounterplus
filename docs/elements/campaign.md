# Campaign

```xml
<campaign id="07D8A58C-52E3-461C-928C-12F45878E60A">
	<name>New Campaign</name>
	<description></description>
	<slug>new-campaign</slug>
	<image></image>
	<module id="AA9B0CA6-E75D-4781-8CA8-CA1DE5B88AB0" ref="/module/examples" />
	<player id="79A826C2-1694-4EEA-92FB-70B0F511BCDD" ref="/player/thorin-stoneheart" />
	<page id="17313864-6B3F-4B93-81A2-3DCD5872FBF1">
		<name>Test Page</name>
		<slug>test-page</slug>
		<content></content>
	</page>
</campaign>
```

## Attributes

| Attribute | Type | Description |
| --------- | ---- | ----------- |
| id  | String  | UUIDv4 |
| sort  | String  | for sorting |

## Fields

| Field  | Type | Description |
| ------ | ---- | ----------- |
| name  | String | |
| slug  | String | for referencing |
| description  | String | |
| image | String | cover image filename |
| module | Reference | asociated module |
| player | Reference | asociated player |
| map | [Map](map.md) |  |
| page | [Page](page.md) |  |
| encounter | [Encounter](encounter.md) |  |
| group | [Group](group.md) |  |

## Content

TODO

