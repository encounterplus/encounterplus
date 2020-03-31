# Import and Export


## Data Format

EncounterPlus is using XML files as a data exchange format, packed into ZIP archive along with other files (images, tokens, fonts, styles, etc..). 

A special file extension can be used for automatic import using Files app or Airdop transfer, although it's not necessary. 

### Compendium

The archive can use `.compendium` file extension and it must contain `compendium.xml` definition file in the root. It can contain `monsters, players, items, spells` folders with images.

* [Compendium ](elements/compendium.md)

Elements: 
* [Monster](elements/monster.md)
* [Player](elements/player.md)
* [Item](elements/item.md)
* [Spell](elements/spell.md)

### Module & Campaign

The archive can use `.campaign` or `.module` file extensins and it must contain `campaign.xml` or `module.xml` file. It can contain multiple folders with various files, which will be copied during import. A special `assets` folder is used for HTML styles, javascript, font and images. 

* [Campaign](elements/campaign.md)
* [Module](elements/module.md)

Elements:
* [Page](elements/page.md)
* [Encounter](elements/encounter.md)
* [Map](elements/map.md)
* [Group](elements/group.md)

### Pack

The archive can use `.pack` file extensins and it must contain `pack.xml` file. It can contain multiple folders with various files, which will be copied during import.

* [Pack](elements/pack.md)

Elements:
* [Asset](elements/asset.md)
* [Group](elements/group.md)