# Pack

```xml
<pack id="8BEBC35E-0C03-4F2B-AAAA-6DA21DC18FAB">
	<name>Sample Assets</name>
	<description>2minutetabletop.com</description>
	<slug>sample-assets</slug>
	<author>2minutetabletop.com</author>
	<code></code>
	<category>other</category>
	<image>cover.png</image>
	<group id="1D5541E9-5C5D-4205-81B9-21E5EA9CBA6D" sort="4">
		<name>Camp</name>
		<slug>Camp</slug>
	</group>
	<asset id="B8E0AE48-2C6D-4D33-A1D0-C2B9D8033A05" parent="1D5541E9-5C5D-4205-81B9-21E5EA9CBA6D">
		<name>Tent, narrow, 1</name>
		<type>image</type>
		<resource>Tent, narrow, 1.png</resource>
	</asset>
	<asset id="4CEB8D71-90E5-40E3-85DF-C039C3EB96A7" parent="1D5541E9-5C5D-4205-81B9-21E5EA9CBA6D">
		<name>26</name>
		<type>image</type>
		<resource>26.png</resource>
	</asset>
	<asset id="90A9AB1F-DB76-4EF1-9EF0-EBF76340C988" parent="1D5541E9-5C5D-4205-81B9-21E5EA9CBA6D">
		<name>28</name>
		<type>image</type>
		<resource>28.png</resource>
	</asset>
</pack>
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
| category  | String | personal, other |
| image | String | cover image filename |
| group | [Group](gruop.md) |  |
| asset | [Asset](asset.md) |  |


