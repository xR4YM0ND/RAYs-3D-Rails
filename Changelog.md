# RAY's 3D Rails Changelog

## 3.1

### Fixed:
- Modern Minecarts Copper Rails `// forgot to apply the copper path changes to modern minecarts`

## 3.0
This took quite a while to get my head around.  
Finally i added **LabPBR shader support** via specular maps.

I used [LabPBR Material Standard](https://shaderlabs.org/wiki/LabPBR_Material_Standard#Specular_Texture_(_s)) as a preset for the specular maps and build on it.

Actual values used - *if someone is interested* - can be found [here](https://github.com/xR4YM0ND/RAYs-3D-Rails/blob/main/assets/rays_3d_rails/info_material.md).  
`// Note that it highly depends on the shader and their LabPBR settings`

*Currently **specular maps** are supported for all textures with 4 variants.*

### Added:
- LabPBR Shader support `// for all existing "4 variants"`

### Updated:
- Alex's Caves `// 4 variants + LabPBR`
- Botania `// 4 variants + LabPBR`
- Create `// LabPBR`

### Fixed:
- Wrong files path for copper models `// changed data structure`
- RP won't load due to unsupported characters in filename `// removed filename colors`

## 2.7

### Added:
- Copper Rails `1.0.5` Support `// up to 4 variants`

## 2.6

### Added:
- Mythic Metals `0.22.1` Support `// up to 4 variants`


## 2.5

### Added:
- More Rail Variants (MStV+) `1.0.4` Support `// up to 4 variants`

## 2.4

### Fixed:
- Create Cart Assembler Compat

## 2.3

### Changed:
- Readded old redstone textures `// instead of rails`

### Added:
- Caverns and Chasms `2.0.0` Support `// up to 4 variants`

## 2.2

### Fixed:
- Wrong vanilla powered rail blockstate

### Added:
- Oxidized `1.8.4` Support `// up to 4 variants`

---

## 2.1

### Added:
- Modern Minecarts `1.1.0` Support `// up to 4 variants`

### Fixed:
- Made models parent `// lowers file size`

---

## 2.0

### Changed:
- Up to 4 different variants for vanilla rails `// modded rails will be reworked in future updates`
- New base wood texture `// also redid rail texture slightly`
- New redstone rails `// instead of flat pixels`
- New folder system `// now material based instead of mod based`
- Every object is now their own texture `// improves file size & performance / also improves particles`
- New `pack.png` logo

### Added:
- Botania (old textures) `// forgot to release v1.9`

---

## 1.8

### Added:
- Spelunkery Support

### Fixed:
- Create waterlogged controller rail

---

## 1.7

### Changed:
- pack.mcmeta

### Added:
- Create Support

---

## 1.6

### Added:
- Little Logistics Support

---

## 1.5

### Added:
- Alex's Caves Support

### Fixed:
- Renamed textures for better compat with Create and maybe more (thx to @TBlazeWarriorT)
- Rails float into the ground (thx to @vaillantoine)
- Some missing particle issues & size issues

---

## 1.4

### Added:
- Useful Railroads Support

---

## 1.3

### Added:
- Thermal Locomotion Support

### Fixed:
- Powered Rail Raised On SW
- Maglev Powered Rail Raised

### Changed:
- Solid to translucent hologram rails (thx to @Xannosz)

---

## 1.2

### Added:
- Xannosz's Better Minecarts Support

---

## 1.1

### Added:
- More Minecarts and Rails Support
- LICENSE

### Changed:
- Removed some models & made the redstone textures parent
- Now the actual 3D items appear
- New pack.mcmeta description

---

## 1.0

### Added:
- Vanilla Support