# Usage

# Create lib
"local lib = loadstring(game:HttpGet('https://raw.githubusercontent.com/loglizzy/lib/main/main.lua'))()"

# Create Window
"local window = lib:Window('title here')"

# Add Toggle
"window:Toggle('toggle', function(enabled)
     print(enabled)
end)"

# Add Slider
"window:Slider('slider', {
     max = 80,
     def = 20
}, function(value)
     print(value)
end)"
