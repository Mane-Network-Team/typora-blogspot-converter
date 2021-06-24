# typora-blogspot-converter

A Plug-in converting readme file to html for google blogspot used only.

## Install

Download [typora](https://typora.io/) and [releases](https://github.com/Mane-Network-Team/typora-blogspot-converter/releases) on your file system.

Install `Python3` and `markdown` modules.

```bash
pip3 install markdown
```

## Add the Typora Support

1. Open `Typora`
2. Click `File` -> `Preferences` -> `Export`  -> `+`  to add one 
3. Type the name like `Mane Blogger`
4. Command line will be 

```bash
<your_patch>\mdToHtml.py -i "${currentPath}" -t default
```

Show Save File Dialog : "`Do not popup save file dialog`"

After Export : Disable the `show command output`

![Setting](\picture\setting.png)

## About the file system

`mdToHtml.py` 

- `-i` : input file
- `-t` : using the template in `template` directory .
- `-v` : show versions

The `template` directory will be save the template files.

## Template (-t)

Version 1.0 only have default template.

- `Default` 

## Developer

Made by Mane.
