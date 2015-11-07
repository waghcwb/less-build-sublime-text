# Creating a build system for Less in Sublime Text .

## Dependencies
* [Less](http://lesscss.org)
* [Sublime Text](http://www.sublimetext.com)

## Lets get hands dirty
* `Tools > Build System > New Build System...`
* Insert the code above on the file:
```json
{
    "cmd": ["lessc", "$file", "$file_base_name.css"]
}
```
* Save it!

----

Thats it! Do you want more? Okay so... :smirk:

## Extras

#### Minified output
upcoming


#### Build all files in a folder
upcoming

## Todo's
- [x] Simple build system.
- [ ] Minified output.
- [ ] Build all file in a folder.