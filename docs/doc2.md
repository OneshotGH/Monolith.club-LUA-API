
# add_callback
### Parameters
| Name       | Type         | Info                                                           |
|------------|--------------|----------------------------------------------------------------|
| Event Name | string       | Callback of CS:GO [Event](https://wiki.alliedmods.net/Counter-Strike:_Global_Offensive_Events) or Cheat Callbacks |
| Function   | Lua Function |                                                                |
### Usage example
```lua
--Will draw a line on the upper left corner of your screen
function on_paint()
    renderer:add_line(vec2.new(15,15),vec2.new(10,10),color.new(255,255,255,255):d3d(),color.new(255,255,255,255):d3d())
end
client.add_callback("on_paint",on_paint)


--Another way of paint
client.add_callback("on_paint",function ()
    renderer:add_line(vec2.new(15,15),vec2.new(10,10),color.new(255,255,255,255):d3d(),color.new(255,255,255,255):d3d())
end)

```


*Last edit by Bronya in 2021/1/17*.

