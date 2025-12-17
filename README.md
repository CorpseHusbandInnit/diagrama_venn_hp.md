# diagrama_venn_hp.md
Venn
# Diagrama de Venn - Objetos mágicos de Harry Potter

```mermaid
venn-beta  
  title "Objetos mágicos de Harry Potter"
  
  set V { label: "Vuela" }
  set H { label: "Habla/Suena" }
  set T { label: "Transforma" }
  
  intersection V H
  intersection V T
  intersection H T
  intersection V H T
  
  -- Solo V --
  V - H - T: "Nimbus 2000"
  V - H - T: "Golden Snitch"

  -- Solo H --
  H - V - T: "Talking Portraits"
  H - V - T: "Mirror of Erised"
  H - V - T: "Talking Ring"
  H - V - T: "Self-Writing Quill"

  -- Solo T --
  T - V - H: "Protean-Charmed Galleon"
  T - V - H: "Transfiguration object"
  T - V - H: "Horcrux"
  T - V - H: "Invisibility Cloak"
  T - V - H: "Boggart"
  T - V - H: "Self-Stirring Cauldron"
  T - V - H: "Knight Bus"
  T - V - H: "Mad-Eye's Trunk"
  T - V - H: "Philosopher's Stone"

  -- V∩H --
  V & H - T: "Sorting Hat"
  V & H - T: "Postal Owl"

  -- V∩T --
  V & T - H: "Floo Powder"
  V & T - H: "Hippogriff"

  -- H∩T --
  H & T - V: "Marauder's Map"

  -- V∩H∩T --
  V & H & T: "Monster Book of Monsters"

  -- Fuera --
  note outside: "Magic Wand"
```
