# blog

This repository store my blog entries. You can use this repository as example to implement it with [web-console](https://github.com/RobertoRojas/web-console).

The standard of the wc files is:

```
# Title

## Subtitle

### Notes

This is a simple line. To modify the color use <span class="black_font white_back">CLASS</span>

## Code section

---
#!/bin/bash

my_function () {
  local func_result="some result"
  echo "$func_result"
}

func_result="$(my_function)"
echo $func_result
---
```
[Standard](https://github.com/RobertoRojas/blog/blob/main/web-console/wvstandard/en/content.wc)

The folders structure must be:

> _root_/topic/entry/language/content.wc

## Colors

### Fonts

```html
<span class='black_font'>black</span>
<span class='white_font'>white</span>
<span class='red_font'>red</span>
<span class='blue_font'>blue</span>
<span class='green_font'>green</span>
<span class='magenta_font'>magenta</span>
<span class='cyan_font'>cyan</span>
<span class='yellow_font'>yellow</span>
```

### Background

```html
<span class='black_back'>black</span>
<span class='white_back'>white</span>
<span class='red_back'>red</span>
<span class='blue_back'>blue</span>
<span class='green_back'>green</span>
<span class='magenta_back'>magenta</span>
<span class='cyan_back'>cyan</span>
<span class='yellow_back'>yellow</span>
```