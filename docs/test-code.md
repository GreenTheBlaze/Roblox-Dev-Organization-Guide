<p class="style-good">Good:
<p class="style-good">
```lua
-- This is good code
if waterLevelTooHigh() then
    drainHangar()
end
```
</p>


# Lua Scripting Style Guide

This style guide shows good and bad examples of Lua code organization and best practices.

---

## Water Level Check

<p class="style-good">
    
Good:

```lua
-- Without this condition, the aircraft hangar would fill up with water.
if waterLevelTooHigh() then
    drainHangar()
end
```
</p>


<p class="style-good">Good:</p>

```lua
-- Without this condition, the aircraft hangar would fill up with water.
if waterLevelTooHigh() then
    drainHangar()
end
```


