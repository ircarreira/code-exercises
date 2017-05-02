
# Parse RGB colors represented by strings.

Implement a function which takes a color as a string in one of the formats described below and returns the parsed color as a map (see #Examples).

# Input:

The input string represents one of the following:

###  6-digit hexadecimal - "#RRGGBB"
#### e.g. "#012345", "#789abc", "#FFA077"

### 3-digit hexadecimal - "#RGB"
#### e.g. "#012", "#aaa", "#F5A"

### Preset color name
#### e.g. "red", "BLUE", "LimeGreen"

# Examples

```
parse_html_color('#80FFA0')   # => { r: 128, g: 255, b: 160 }
parse_html_color('#3B7')      # => { r: 51,  g: 187, b: 119 }
parse_html_color('LimeGreen') # => { r: 50,  g: 205, b: 50  }
```
