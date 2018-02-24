# CSS Select

This are pure CSS and HTML implementation concepts of a select form control element. They provide a way to style select options consistently cross browsers.

## Caveats
- Additional markup
- Forced to `checked` a default value
- fixed min-height min-width

There are three levels of browser support:

- [Legacy]()

  for all devices that do not support `:focus` or `:active`

  - Only closed if a value is clicked
  - using an additional radio option to toggle the options 

- [Blubble]()

  for all the devices that do not *blubble* `:active` to parents (IE10)

- [cssselect]()
  
  for all others