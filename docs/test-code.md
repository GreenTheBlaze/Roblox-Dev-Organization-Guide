<div class="codehilite" id="__code_65"><button class="md-clipboard" title="Copy to clipboard" data-clipboard-target="#__code_65 pre, #__code_65 code"><span class="md-clipboard__message"></span></button><pre><span></span><span class="c1">-- Without this condition, the aircraft hangar would fill up with water.</span>
<span class="kr">if</span> <span class="n">waterLevelTooHigh</span><span class="p">()</span> <span class="kr">then</span>
    <span class="n">drainHangar</span><span class="p">()</span>
<span class="kr">end</span>
</pre></div>


<p class="style-good">Good:</p>

```lua class="good"
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
