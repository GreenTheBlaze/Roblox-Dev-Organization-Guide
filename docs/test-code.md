<p class="style-good">Good:</p>

```lua hl_lines="1 2 3" class="good"
-- Without this condition, the aircraft hangar would fill up with water.
if waterLevelTooHigh() then
    drainHangar()
end
```



# Lua Scripting Style Guide

This style guide shows good and bad examples of Lua code organization and best practices.

---

## Water Level Check

<p class="style-good">Good:</p>

```lua {.good}
-- Without this condition, the aircraft hangar would fill up with water.
if waterLevelTooHigh() then
    drainHangar()
end
```
