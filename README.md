# Simple PBR Generator

I developed this simple script in order to generate Normal, Ambient Oclusion and Height maps using any kind of texture image. 
I'm currently using this to generate theses maps over pixel art textures and for this purpose works really great.

Feel free to make any adjustments and use freely in your indie-game. Have fun!

## Requirements
Install using Python3 PIP.

`python3 -m pip install -r requirements.txt`

## Usage
```
simple_pbr_generator.py [-h] [-o OUTPUT_FILE] [-s SMOOTH] [-it INTENSITY] input_file
simple_pbr_generator.py: error: the following arguments are required: input_file

```

## Basic Example
`python3 simple_pbr_generator.py ~/my-awesome-retro-game/HLTX0952.png`

The output will be `HLTX0952_normal.png`, `HLTX0952_height.png` and `HLTX0952_ao.png`.

![Example Image](https://i.imgur.com/xzSD549.png)

---
Murilo Mac 2022