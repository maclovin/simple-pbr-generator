# Simple PBR Generator

I developed this simple script in order to generate Normal, Ambient Oclusion and Height maps using any kind of texture image. 
I'm currently using this to generate theses maps over pixel art textures and for this purpose works really great.

Feel free to make any adjustments and use freely in your indie-game. Have fun!

## Requirements
Install using Python3 PIP.

```console
python3 -m pip install -r requirements.txt
```

## Usage
```console
python3 simple_pbr_generator.py input_file [-h] [-o OUTPUT_FILE] [-s SMOOTH] [-it INTENSITY]
```

## Basic Example
```console
python3 simple_pbr_generator.py ~/my-awesome-retro-game/HLTX0952.png
```

The output will be `HLTX0952_normal.png`, `HLTX0952_height.png` and `HLTX0952_ao.png`.

![Example Image](https://i.imgur.com/xzSD549.png)

---
Murilo Mac 2022
