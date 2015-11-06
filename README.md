# Creating a Sublime Text build system for Less.

----

## Dependencies
1. [Less](http://lesscss.org)
2. [Sublime Text](http://www.sublimetext.com)

----

## Lets get hands dirty
1. `Tools > Build System >New Build System...`
2. Insert the code above on the file:

```json
{
    "cmd": ["lessc", "$file", "$file_base_name.css"]
}
```

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