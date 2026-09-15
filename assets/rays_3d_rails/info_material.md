# Notes for LabPBR Material Standard
## Infos
[LabPBR Material Standard Specular Texture](https://shaderlabs.org/wiki/LabPBR_Material_Standard#Specular_Texture_(_s))  

Red Channel = 0 - 255 (smoothness) // 255 = 100% smoothness  
Green Channel = 0 - 255 (reflectance) // 230+ Metals // 229 = 100% reflectance  
Blue Channel = 0 - 64 (porosity) // 64 = 100% porosity // water absorption  
Blue Channel = 65 - 255 (subsurface scattering) // 255 = 100% scattering  
Alpha Channel = 0 - 254 (emissive) // 255 = 0 // 254 = 100% emissive  

`Alpha channel in gimp -> Colors -> Components -> Decompose -> Color model = RGBA`

## Metals

- **Copper**  
Red = 170 #aaaaaa  
Green = 234 #eaeaea  
Blue = 0  

- **Exposed Copper**  
Red = 110  #6e6e6e  
Green = 180 #b4b4b4  
Blue = 0   

- **Weathered Copper**  
Red = 60 #3c3c3c  
Green = 80 #505050  
Blue = 0  

- **Oxidized Copper**  
Red = 20 #141414  
Green = 0  
Blue = 0  

- **Iron**
Red = 200 #c8c8c8  
Green = 230 #e6e6e6  
Blue = 0  

- **Gold**  
Red = 231 #e7e7e7  
Green = 231 #e7e7e7  
Blue = 0  

- **Palladium**  
Red = 237  #ededed  
Green = 237  #ededed  
Blue = 0  

## Materials

- **Redstone** Unlit  
Red = 120 #787878  
Green = 0  
Blue = 0  

- **Redstone** Lit  
Red = 120 #787878  
Green = 0  
Blue = 0  
Alpha = 254 #fefefe  

- **Stone**  
Red = 25 #191919  
Green = 0  
Blue = 0  

- **Planks**  
Red = 40 #282828  
Green = 0  
Blue = 12 #0c0c0c  

## Special Materials  

- **Ghost** (Botania)  
Red = 220 = #dcdcdc // 255  
Green = 140 = #8c8c8c // 255  
Blue = 0  

- **Magnetic Levitation**  
Red = 245 = #f5f5f5  
Green = 140 = #8c8c8c  
Blue = 0  

- **Spike** (uses iron)  
Red = 200 #c8c8c8  
Green = 230 #e6e6e6  
Blue = 0  

- **Brakes**  
Red = 20 = #141414
Green = 0
Blue = 60 = #3d3d3d

- **Ender Pearl**
Red = 48 = 313131  
Green = 25 = 191919  
Blue = 48 = 313131  
Alpha = 20 = 151515  (off)
Alpha = 60 = 3d3d3d  (on)  

- **Electric**
Red = 250 = fbfbfb  
Green = 0  
Blue = 0  

- **Yellow painted steel**
Red = 200 #c8c8c8  
Green = 45 = 2e2e2e  
Blue = 0  

- **Reinforced (Railcraft)**
Red = 160 = a1a1a1  
Green = 30 = 1e1e1e  
Blue = 0  
