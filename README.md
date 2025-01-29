# loading the ui

```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/CoolManYesYes/RealUiLib/refs/heads/main/Source.lua"))()
````

# making a window

```lua
local window = library:init("Titlebar", true, Enum.KeyCode.RightShift, true)
```

# making a divider

```lua
window:Divider("I'm a divider!")
```

# making a section

```lua
local sectionA = window:Section("Test Elements")
```
# making a button

```lua
sectionA:Button("Click me!", function()
   print("Button clicked.")
end)
```

# making a label

```lua
sectionA:Label("Lorem ipsum dolor sit amet.")
```
# making a toggle

```lua
sectionA:Switch("Switch me!", false, function(a)
   print(a)
end)
```
