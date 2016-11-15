Jekyll plugin to compile Typescript
====

## Setup

1. Add *jekyll_ts.rb* to _plugins folder
2. Add plugin configs to your _config.yml file
    * tsc:     path of typescript compiler
3. Javascript files will write to js_dest location on build

## Update

Plugin will maintain the same route of the .js file respect to the .ts file

```
_source/my_folder/ts/file.ts

# will be saved as

_site/my_folder/js/file.js
```
