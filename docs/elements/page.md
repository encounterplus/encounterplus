# Page

```XML
<page id="2BA4481B-B606-4084-9AF6-7DC70AB88A05">
    <name>Example Page</name>
    <slug>example-page</slug>
    <content>
        &lt;p&gt;&lt;img src=&quot;heading.png&quot; alt=&quot;heading&quot; class=&quot;size-cover&quot;&gt;&lt;/p&gt;
        &lt;h1 id=&quot;heading-1&quot;&gt;Heading 1&lt;/h1&gt;
        &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Massa tempor nec feugiat nisl pretium fusce id. Tincidunt augue interdum velit euismod. Odio pellentesque diam volutpat commodo sed egestas. Mattis molestie a iaculis at erat. Nibh venenatis cras sed felis. Dignissim enim sit amet venenatis urna cursus eget nunc scelerisque.&lt;/p&gt;
        &lt;h2 id=&quot;heading-2&quot;&gt;Heading 2&lt;/h2&gt;
        &lt;p&gt;Eu consequat ac felis donec et odio pellentesque. Nullam ac tortor vitae purus faucibus ornare suspendisse. Pellentesque &lt;a href=&quot;/monster/goblin&quot;&gt;habitant&lt;/a&gt; morbi tristique senectus et netus. Mi bibendum neque egestas congue quisque egestas diam in. Donec pretium vulputate sapien nec sagittis aliquam malesuada bibendum arcu.&lt;/p&gt;
        &lt;blockquote class=&quot;read&quot;&gt;
        &lt;p&gt;A condimentum vitae sapien pellentesque habitant morbi tristique. Ut pharetra sit amet aliquam. Consectetur libero id faucibus nisl. Et pharetra pharetra massa massa ultricies mi quis.&lt;/p&gt;
    </content>
</page>
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
| content  | String | HTML content, escaped using [XML Escape](https://www.freeformatter.com/xml-escape.html)  |

## Content

```HTML
<p><img src="heading.png" alt="heading" class="size-cover"></p>
<h1 id="heading-1">Heading 1</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Massa tempor nec feugiat nisl pretium fusce id. Tincidunt augue interdum velit euismod. Odio pellentesque diam volutpat commodo sed egestas. Mattis molestie a iaculis at erat. Nibh venenatis cras sed felis. Dignissim enim sit amet venenatis urna cursus eget nunc scelerisque.</p>
<h2 id="heading-2">Heading 2</h2>
<p>Eu consequat ac felis donec et odio pellentesque. Nullam ac tortor vitae purus faucibus ornare suspendisse. Pellentesque <a href="/monster/goblin">habitant</a> morbi tristique senectus et netus. Mi bibendum neque egestas congue quisque egestas diam in. Donec pretium vulputate sapien nec sagittis aliquam malesuada bibendum arcu.</p>
<blockquote class="read">
  <p>A condimentum vitae sapien pellentesque habitant morbi tristique. Ut pharetra sit amet aliquam. Consectetur libero id faucibus nisl. Et pharetra pharetra massa massa ultricies mi quis.</p>
  <p>Dictumst quisque sagittis purus sit amet volutpat consequat. Cursus turpis massa tincidunt dui ut ornare lectus sit amet. Varius quam quisque id diam vel quam elementum. Feugiat vivamus at augue eget arcu dictum varius.</p>
</blockquote>
<p>Elit eget gravida cum sociis natoque. Quam adipiscing vitae proin sagittis nisl. Vivamus at augue eget arcu dictum varius duis at consectetur. Massa massa ultricies mi quis. Ut faucibus pulvinar elementum integer enim.</p>
<blockquote>
  <p><strong>HEADING</strong></p>
  <p>Pretium lectus quam id leo in vitae turpis massa. Nunc scelerisque viverra mauris in aliquam. Lacus viverra vitae congue eu consequat.</p>
  <p>Semper risus in hendrerit gravida rutrum quisque non tellus. Vel fringilla est ullamcorper eget nulla facilisi etiam. Neque laoreet suspendisse interdum consectetur. Bibendum neque egestas congue quisque egestas diam in arcu cursus.</p>
</blockquote>
<p>Mauris pellentesque pulvinar pellentesque habitant morbi tristique. Non quam lacus suspendisse faucibus interdum posuere. Lacus luctus accumsan tortor posuere ac ut. Ultricies mi eget mauris pharetra et. Eget arcu dictum varius duis at consectetur lorem donec. Nisl nunc mi ipsum faucibus vitae aliquet nec ullamcorper. Nisi vitae suscipit tellus mauris a diam.</p>
<h3 id="heading-3">Heading 3</h3>
<p>Mauris pellentesque pulvinar pellentesque habitant morbi tristique. Non quam lacus suspendisse faucibus interdum posuere. Lacus luctus accumsan tortor posuere ac ut. Ultricies mi eget mauris pharetra et. Eget arcu dictum varius duis at consectetur lorem donec. Nisl nunc mi ipsum faucibus vitae aliquet nec ullamcorper. Nisi vitae suscipit tellus mauris a diam.</p>
<p><img src="hero.jpg" alt="hero"></p>
<p>Curabitur vitae nunc sed velit. Porttitor lacus luctus accumsan tortor posuere ac ut consequat. Convallis convallis tellus id interdum velit. Rutrum tellus pellentesque eu tincidunt. Auctor eu augue ut lectus arcu bibendum at. Integer malesuada nunc vel risus commodo viverra maecenas accumsan lacus. Morbi non arcu risus quis varius quam quisque id. Quis viverra nibh cras pulvinar.</p>
<h4 id="heading-4">Heading 4</h4>
<p>Sit amet dictum sit amet justo donec enim diam vulputate. Iaculis urna id volutpat lacus laoreet non curabitur. Lorem dolor sed viverra ipsum nunc aliquet. Tempus urna et pharetra pharetra massa.</p>
<p>
  <table>
        <thead>
            <tr>
                <th>d100</th>
                <th>Magic Item</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>01–50</td>
                <td>Potion of healing</td>
            </tr>
            <tr>
                <td>51–60</td>
                <td>Spell scroll (cantrip)</td>
            </tr>
            <tr>
                <td>61–70 </td>
                <td>Potion of climbing</td>
            </tr>
            <tr>
                <td>71–90 </td>
                <td>Spell scroll (1st level)</td>
            </tr>
            <tr>
                <td>91–94</td>
                <td>Spell scroll (2nd level)</td>
            </tr>
            <tr>
                <td>95–98</td>
                <td>Potion of greater healing</td>
            </tr>
            <tr>
                <td>99</td>
                <td>Bag of holding</td>
            </tr>
            <tr>
                <td>00</td>
                <td>Driftglobe</td>
            </tr>
        </tbody>
    </table>
</p>
```