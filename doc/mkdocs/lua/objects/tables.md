
[TOC]

---
## Table Manipulation

Object instance: `table`

---
### Description

The following methods have been added to the built-in Lua
[table library](https://www.lua.org/manual/5.3/manual.html#6.6).

## Methods

---
### table.clean
<div class="function">
    table.clean <span class="params">(tbl)</span>
</div>

- Removes [nil][LuaNil] values from a table.
- Parameters:
    - ___tbl:__ ([table][LuaTable])_ The table to be cleaned.
- Returns: _([table][LuaTable])_
    - Copy of ___tbl___ with `nil` values removed.

---
### table.concat
<div class="function">
    table.concat <span class="params">(tbl1, tbl2)</span>
</div>

- Merges the contents of one table into another.
- Parameters:
    - ___tbl1:__ ([table][LuaTable])_ The table receiving the new content.
    - ___tbl2:__ ([table][LuaTable])_ The table containing the content to be copied.

---
### table.contains
<div class="function">
    table.contains <span class="params">(table, o)</span>
</div>

- Checks if a table contains a value.
- Parameters:
    - ___table:__ ([table][LuaTable])_ Table to be checked.
    - ___obj:__ ([Object][java.lang.Object])_ The object to check for.
- Returns: _([bool][LuaBoolean])_
    - `true` if ___obj___ is in ___table___.

---
### table.join
<div class="function">
    table.join <span class="params">(table, delim)</span>
</div>

- Joins a table of strings into a string.
- Parameters:
    - ___table:__ ([table][LuaTable])_ Table to be joined.
    - ___delim:__ ([string][LuaString]) Character(s) to be used as separator.
- Returns: ([string][LuaString])
    - The resulting string.


[java.lang.Object]: https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/Object.html

[LuaBoolean]: http://luaj.org/luaj/3.0/api/org/luaj/vm2/LuaBoolean.html
[LuaNil]: http://luaj.org/luaj/3.0/api/org/luaj/vm2/LuaNil.html
[LuaString]: http://luaj.org/luaj/3.0/api/org/luaj/vm2/LuaString.html
[LuaTable]: http://luaj.org/luaj/3.0/api/org/luaj/vm2/LuaTable.html
