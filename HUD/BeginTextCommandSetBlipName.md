---
ns: HUD
---
## BEGIN_TEXT_COMMAND_SET_BLIP_NAME

```c
// 0xF9113A30DE5C6670 0xF4C211F6
void BEGIN_TEXT_COMMAND_SET_BLIP_NAME(char* gxtentry);
```

```
example:  
UI::BEGIN_TEXT_COMMAND_SET_BLIP_NAME("STRING");  
UI::_ADD_TEXT_COMPONENT_STRING("Name");  
UI::END_TEXT_COMMAND_SET_BLIP_NAME(blip);  
```

## Parameters
* **gxtentry**: 

