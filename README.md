# Metro Config

🚇 Config resolver and transformer for [Metro](https://facebook.github.io/metro/).

## hotfix

https://github.com/facebook/metro/issues/453

for who still get this error without official patch in react-native , expo

use yarn and add this setting into package.json

```json
{
  ...
  "resolutions": {
    "metro-config": "bluelovers/metro-config-hotfix-0.56.x"
  },
 ...
```
