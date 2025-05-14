!!! exception "Exception:"
    ```lua
    error("Unexpected input")
    ```

!!! bad "Bad:"
    ```lua
    local x = 1/0
    ```

!!! good "Good:"
    ```lua
    local function safeDivide(a, b)
      return b ~= 0 and a / b or nil
    end
    ```
