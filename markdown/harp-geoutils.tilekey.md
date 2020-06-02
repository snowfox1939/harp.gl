<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-geoutils](./harp-geoutils.md) &gt; [TileKey](./harp-geoutils.tilekey.md)

## TileKey class

The `TileKey` instances are used to address a tile in a quadtree.

A tile key is defined by a row, a column, and a level. The tree has a root at level 0, with one single tile. On every level, each tile is divided into four children (therefore the name quadtree).

Within each \[\[level\]\], any particular tile is addressed with \[\[row\]\] and \[\[column\]\]. The number of rows and columns in each level is 2 to the power of the level. This means: On level 0, only one tile exists, \[\[columnsAtLevel\]\]() and \[\[rowsAtLevel\]\]() are both 1. On level 1, 4 tiles exist, in 2 rows and 2 columns. On level 2 we have 16 tiles, in 4 rows and 4 columns. And so on.

A tile key is usually created using \[\[fromRowColumnLevel\]\]() method.

`TileKey` instances are immutable, all members return new instances of `TileKey` and do not modify the original object.

Utility functions like \[\[parent\]\](), \[\[changedLevelBy\]\](), and \[\[changedLevelTo\]\]() allow for easy vertical navigation of the tree. The number of available rows and columns in the tile's level is given with \[\[rowCount\]\]() and \[\[columnCount\]\]().

Tile keys can be created from and converted into various alternative formats:

- \[\[toQuadKey\]\]() / \[\[fromQuadKey\]\]() - string representation 4-based - \[\[toHereTile\]\]() / \[\[fromHereTile\]\]() - string representation 10-based - \[\[mortonCode\]\]() / \[\[fromMortonCode\]\]() - number representation

Note - as JavaScript's number type can hold 53 bits in its mantissa, only levels up to 26 can be represented in the number representation returned by \[\[mortonCode\]\]().

<b>Signature:</b>

```typescript
export declare class TileKey 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(row, column, level)](./harp-geoutils.tilekey._constructor_.md) |  | Constructs a new immutable instance of a <code>TileKey</code>.<!-- -->For the better readability, \[\[TileKey.fromRowColumnLevel\]\] should be preferred.<!-- -->Note - row and column must not be greater than the maximum rows/columns for the given level. |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [column](./harp-geoutils.tilekey.column.md) |  | number |  |
|  [level](./harp-geoutils.tilekey.level.md) |  | number |  |
|  [row](./harp-geoutils.tilekey.row.md) |  | number |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [addedSubHereTile(sub)](./harp-geoutils.tilekey.addedsubheretile.md) |  | Returns the absolute quadkey that is constructed from its sub HERE tile key. |
|  [addedSubKey(sub)](./harp-geoutils.tilekey.addedsubkey.md) |  | Returns the absolute quadkey that is constructed from its sub quadkey. |
|  [atCoords(level, coordX, coordY, totalWidth, totalHeight)](./harp-geoutils.tilekey.atcoords.md) | <code>static</code> | Returns the closest matching <code>TileKey</code> in a cartesian coordinate system. |
|  [changedLevelBy(delta)](./harp-geoutils.tilekey.changedlevelby.md) |  | Returns a new tile key at a level that differs from this tile's level by delta.<!-- -->Equivalent to <code>changedLevelTo(level() + delta)</code>.<!-- -->Note - root key is returned if <code>delta</code> is smaller than the level of this tile key. |
|  [changedLevelTo(level)](./harp-geoutils.tilekey.changedlevelto.md) |  | Returns a new tile key at the requested level.<!-- -->If the requested level is smaller than the tile's level, then the key of an ancestor of this tile is returned. If the requested level is larger than the tile's level, then the key of first child or grandchild of this tile is returned, for example, the child with the lowest row and column number. If the requested level equals this tile's level, then the tile key itself is returned. If the requested level is negative, the root tile key is returned. |
|  [columnCount()](./harp-geoutils.tilekey.columncount.md) |  | Returns the number of available columns in the tile's \[\[level\]\].<!-- -->This is 2 to the power of the level. |
|  [columnsAtLevel(level)](./harp-geoutils.tilekey.columnsatlevel.md) | <code>static</code> | Returns the number of available columns at a given level.<!-- -->This is 2 to the power of the level. |
|  [equals(qnr)](./harp-geoutils.tilekey.equals.md) |  | Equality operator. |
|  [fromHereTile(quadkey64)](./harp-geoutils.tilekey.fromheretile.md) | <code>static</code> | Creates a tile key from a heretile code string.<!-- -->The string can be created with \[\[toHereTile\]\]. |
|  [fromMortonCode(quadKey64)](./harp-geoutils.tilekey.frommortoncode.md) | <code>static</code> | Creates a tile key from a numeric Morton code representation.<!-- -->You can convert a tile key into a numeric Morton code with \[\[mortonCode\]\]. |
|  [fromQuadKey(quadkey)](./harp-geoutils.tilekey.fromquadkey.md) | <code>static</code> | Creates a tile key from a quad string.<!-- -->The quad string can be created with \[\[toQuadKey\]\]. |
|  [fromRowColumnLevel(row, column, level)](./harp-geoutils.tilekey.fromrowcolumnlevel.md) | <code>static</code> | Creates a tile key. |
|  [getSubHereTile(delta)](./harp-geoutils.tilekey.getsubheretile.md) |  | Returns a sub quadkey that is relative to its parent.<!-- -->This function can be used to generate sub keys that are relative to a parent that is delta levels up in the quadtree.<!-- -->This function can be used to create shortened keys for quads on lower levels if the parent is known.<!-- -->Note - the sub quadkeys fit in a 16-bit unsigned integer if the <code>delta</code> is smaller than 8. If <code>delta</code> is smaller than 16, the sub quadkey fits into an unsigned 32-bit integer.<!-- -->Deltas larger than 16 are not supported. |
|  [mortonCode()](./harp-geoutils.tilekey.mortoncode.md) |  | Converts the tile key to a numeric code representation.<!-- -->You can create a tile key from a numeric Morton code with \[\[fromMortonCode\]\].<!-- -->Note - only levels less than or equal to 26 are supported. |
|  [parent()](./harp-geoutils.tilekey.parent.md) |  | Returns a tile key representing the parent of the tile addressed by this tile key.<!-- -->Throws an exception is this tile is already the root. |
|  [parentMortonCode(mortonCode)](./harp-geoutils.tilekey.parentmortoncode.md) | <code>static</code> | Computes the Morton code of the parent tile key of the given Morton code.<!-- -->Note: The parent key of the root key is the root key itself. |
|  [rowCount()](./harp-geoutils.tilekey.rowcount.md) |  | Returns the number of available rows in the tile's \[\[level\]\].<!-- -->This is 2 to the power of the level. |
|  [rowsAtLevel(level)](./harp-geoutils.tilekey.rowsatlevel.md) | <code>static</code> | Returns the number of available rows at a given level.<!-- -->This is 2 to the power of the level. |
|  [toHereTile()](./harp-geoutils.tilekey.toheretile.md) |  | Converts the tile key into a string for using in REST API calls.<!-- -->The string is a quadkey Morton code representation as a string.<!-- -->You can convert back from a quadkey string with \[\[fromHereTile\]\]. |
|  [toQuadKey()](./harp-geoutils.tilekey.toquadkey.md) |  | Converts the tile key into a string for using in REST API calls.<!-- -->If the tile is the root tile, the quadkey is '-'. Otherwise the string is a number to the base of 4, but without the leading 1, with the following properties: 1. the number of digits equals the level. 2. removing the last digit gives the parent tile's quadkey string, i.e. appending 0,1,2,3 to a quadkey string gives the tiles's children.<!-- -->You can convert back from a quadkey string with \[\[fromQuadKey\]\]. |
