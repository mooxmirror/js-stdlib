JavaScript Standard Container Library
==============================

The JSCL provides a standard set of data structure and algorithm implementations to help JS devs by removing boilerplate code.

### Be careful
> This is development level software.  Please do not unless you are
> familiar with what that means and are comfortable using that type
> of software.

Usage
-----------------
Install the package using `bower install jscl`. There should be a `lib` folder containing the minified and the standard version of the library. Just include it using the `<script>` tag.

Data structures
-----------------
###Common methods
- `empty()` checks if the data structure has no content
- `size()` returns the count of elements that the object contains
- `clear()` deletes all objects in the container

###Included data structures
- Stacks (`push(obj)` | `pop()` | `peek()` | `empty()` | `size()` | `clear()`)
- Queue (`offer(obj)`| `poll()`| `peek()` | `empty()` | `size()`| `clear()`)

---------------------------------------------------------------------------------------------------
[License (MIT)](./LICENSE.txt)
