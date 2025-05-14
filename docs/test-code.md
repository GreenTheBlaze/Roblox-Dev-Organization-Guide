# Lua Scripting Style Guide

This style guide shows good and bad examples of Lua code organization and best practices.

---

## Water Level Check

<p class="style-good">Good:</p>

<div class="highlight good"><pre><code class="language-lua">-- Without this condition, the aircraft hangar would fill up with water.
if waterLevelTooHigh() then
    drainHangar()
end
</code></pre></div>

<p class="style-bad">Bad:</p>

<div class="highlight bad"><pre><code class="language-lua">-- This will flood the hangar if water level rises.
drainHangar()
</code></pre></div>

---

## Proper Use of Local Variables

<p class="style-good">Good:</p>

<div class="highlight good"><pre><code class="language-lua">local count = 0
for i = 1, 10 do
    count += i
end
</code></pre></div>

<p class="style-bad">Bad:</p>

<div class="highlight bad"><pre><code class="language-lua">count = 0 -- polluting global scope
for i = 1, 10 do
    count += i
end
</code></pre></div>

---

## Function Naming

<p class="style-good">Good:</p>

<div class="highlight good"><pre><code class="language-lua">function calculateScore(player)
    -- logic here
end
</code></pre></div>

<p class="style-bad">Bad:</p>

<div class="highlight bad"><pre><code class="language-lua">function cS(p)
    -- unclear purpose and names
end
</code></pre></div>
