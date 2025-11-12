# zippopotam
api for zippopotam.us Free, open-source postal code and ZIP code lookup site
# Example
```nim
import asyncdispatch, zippopotam, json, strutils
let data = waitFor search_index("country",index)
echo data
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```
