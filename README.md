 # Usage
 
 Create lib
 ```lua
local lib = loadstring(game:HttpGet('https://raw.githubusercontent.com/Txhx213/TaptUI/main/main'))()
```
 Create Window
 ```lua
 local window = lib:Window('title here')
 ```
 Add Toggle
 ```lua
 window:Toggle('toggle', function(enabled)
     print(enabled)
end)
 ```
 
 Add Slider
```lua
window:Slider('slider', {
     max = 80,
     def = 20
}, function(value)
     print(value)
end)
```
