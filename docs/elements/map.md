# Map

```xml
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
    <tile id="0D5300D6-AEA3-4740-AE0D-3B61E3845E43">
        <x>400</x>
        <y>475</y>
        <width>150</width>
        <height>150</height>
        <rotation>0</rotation>
        <opacity>1.0</opacity>
        <layer>object</layer>
        <zIndex>0</zIndex>
        <hidden>NO</hidden>
        <locked>NO</locked>
        <asset id="3D1AAEF4-BC98-4D32-9FB7-F83FC71EFAE9">
            <name>11</name>
            <type>image</type>
            <resource>11.png</resource>
        </asset>
    </tile>
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
    <tile id="4343DA6B-F468-4CC5-A73E-8851C7519E2D">
        <x>165</x>
        <y>626</y>
        <width>131</width>
        <height>153</height>
        <rotation>0</rotation>
        <opacity>1.0</opacity>
        <layer>map</layer>
        <zIndex>0</zIndex>
        <hidden>NO</hidden>
        <locked>NO</locked>
        <asset id="FF39C74A-721D-4395-86E7-702F77EFD571">
            <name>Bush, shrub, 2</name>
            <type>image</type>
            <resource>Bush, shrub, 2.png</resource>
        </asset>
    </tile>
    <tile id="7D8B0F2F-32EE-4B2F-A7A0-2F9145F84A95">
        <x>594</x>
        <y>519</y>
        <width>52</width>
        <height>145</height>
        <rotation>45</rotation>
        <opacity>1.0</opacity>
        <layer>token</layer>
        <zIndex>0</zIndex>
        <hidden>NO</hidden>
        <locked>NO</locked>
        <asset id="34991563-F9A0-48F1-BB55-F9041594CAFB">
            <name>Canoe</name>
            <type>image</type>
            <resource>Canoe.png</resource>
        </asset>
    </tile>
</map>

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
| descr  | String | |
| gridSize  | Integer |  |
| gridOffsetX | Integer |  |
| gridOffsetY | Integer |  |
| gridColor | String | HEX format, #CCCCCC |
| gridVisible | Boolean | YES, NO |
| image | String | backgorund image filename |
| video | String | background video filename |
| scale | Float |  |
| x | Integer | position |
| y | Integer | position |
| zoom | Float |  |
| canvas | String | canvas filename |
| snapshot | String | snapshot filename (deprecated) |
| floor | String | floor filename |
| fogVisible | Boolean | YES, NO |
| fog | String | fog filename |
| lineOfSight | Boolean | YES, NO |
| daylight | Float | for line of sight calculations |
| marker | [Marker](marker.md) |  |
| tile | [Tile](tile.md) |  |

## Canvas

Map drawings are stored in the single SVG image, containing only basic path elements. Each shape can be placed on a different layer using the `class` attribute. Possible values are `dm, object, token, map, wall`.

```xml
<svg height="1308.0" version="1.0" width="1202.0" xmlns="http://www.w3.org/2000/svg">
    <path d="M462.00,1007.00L462.00,1007.00L461.50,1007.00L465.50,989.00L481.00,949.50L490.00,930.00L502.50,908.00L509.00,901.50L512.00,901.00L510.50,922.00L495.50,955.00L477.50,998.50L474.00,1009.50L491.00,990.50L518.50,956.50L526.50,947.00L530.00,943.50L526.50,955.50L517.00,974.00L509.00,991.00L503.50,1004.50L503.00,1007.50L536.50,970.00L542.50,965.00L537.00,979.00L530.50,991.50L527.50,999.50L527.50,1001.50L530.00,1001.50L570.00,976.50L585.00,970.50L581.00,980.50L572.00,996.00L568.00,1005.00L567.00,1008.50L581.00,1008.50L598.50,1004.00L609.50,1003.00L615.00,1004.50L615.00,1012.50L609.00,1028.00L599.00,1047.50" fill="none" stroke="#000000" stroke-linecap="round" stroke-linejoin="round" stroke-opacity="1.0" stroke-width="3.0"/>
    <path d="M568.50,914.50L568.50,914.50L573.00,913.50L576.00,911.50L570.50,925.50L561.00,945.00L560.50,948.00L574.00,935.50L598.00,915.50L604.50,911.00L607.50,909.50L605.50,915.50L596.50,929.00L595.50,932.50L607.00,927.00L618.50,920.00L630.00,914.50L625.00,927.00L621.00,933.00L617.00,940.50L628.50,938.50L647.00,931.00L656.00,928.50L658.50,928.50L657.00,935.00L633.50,972.00L635.50,972.50L664.00,961.00L663.50,963.50L653.00,978.00L653.00,980.00L679.00,979.50L677.50,987.00L669.00,996.00L663.00,1004.00L662.00,1006.00L671.00,1006.00" fill="none" stroke="#00ff00" stroke-linecap="round" stroke-linejoin="round" stroke-opacity="0.3" stroke-width="20.0"/>
    <path class="wall" d="M491.93,767.04L491.93,767.04L539.75,740.94L546.56,759.23L538.18,774.42L510.59,783.88L495.32,777.11L498.10,763.30" fill="none" stroke="#ff7f00" stroke-linecap="round" stroke-linejoin="round" stroke-opacity="1.0" stroke-width="3.0"/>
    <path class="wall" d="M537.52,430.54L537.52,430.54L558.63,418.68L577.10,394.45L580.90,416.83L570.66,438.30L550.07,445.23L542.09,429.47" fill="none" stroke="#ff7f00" stroke-linecap="round" stroke-linejoin="round" stroke-opacity="1.0" stroke-width="3.0"/>
    <path  class="object" stroke="#000000" stroke-opacity="1.0" stroke-width="3.0" stroke-linejoin="round" stroke-linecap="round" fill="none" d="M680.02,747.61L680.02,747.61L681.93,745.56L693.71,739.95L698.42,739.37L728.11,739.37L736.15,746.91L744.53,757.97L752.14,763.53L757.61,765.52L765.33,766.08L775.64,766.08L780.34,765.49L788.35,762.67L794.86,758.88L799.76,756.68" />
    <path  class="map" stroke="#000000" stroke-opacity="1.0" stroke-width="3.0" stroke-linejoin="round" stroke-linecap="round" fill="none" d="M754.89,825.72L754.89,825.72L792.55,825.72L794.95,826.20L798.61,828.52L805.77,834.81L808.57,836.38L811.07,836.76L815.38,836.76L818.92,835.87L823.68,833.02L831.68,827.12" /></svg>
</svg>

```

## Floor

Map floor is stored in the single PNG image, where single pixel represents one grid tile. Pixels could be in different colors denoting different type of floor. (Floors can be used to automatically generate walls.)

## Fog of War

Fog of war is stored in the single PNG image, where white areas represent visible areas, and transparent areas represent hidden parts (image is used as mask).

