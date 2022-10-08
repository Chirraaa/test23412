# WMCP

## Refactoring

1. Remove Big chunks of CSS into modules or external files e.g.
```
/css/pages/items.php.css
```

2. Remove Big chunks of JS into modules or external files e.g.
```
/js/pages/edit_item.php.js
```

3. Remove any game/platform specific code into modules

4. Keep parity between items.inc.php and items.lite.inc.php

5. Add Event::trigger where useful even if you don't need it

## Merging

Merge from a pull request to main from a seperate branch, e.g. adams-branch# test23412
# test23412
# test23412
