# MEU Immersive Vehicles Additions

## Dodawanie nowych rejestracji lub innych elementów
### Rejestracje

Szablon pliku JSON dla rejestracji 
````
{
"generic": {
"type": "generic_licenseplate_euro"
},
"custom": {
"width": 0.25,
"height": 0.25
},
"definitions": [
{
"subName": "",
"modelName": "plate_eu",
"name": "NAZWA ITEMU",
"extraMaterials": []
}
],
"rendering": {
"textObjects": [
{
"pos": [0.045,0.038,0.001],
"rot": [0.0,0.0,0.0],
"scale": 0.18,
"fieldName": "License Plate",
"defaultText": "DOMYŚLNY TEKST NA REJESTRACJI",
"maxLength": 8,
"color": "000000"
}
],
"lightObjects": [],
"particles": [],
"modelType": "obj"
},
"general": {
"name": "NAZWA ITEMU",
"description": "OPIS",
"health": 100,
"materials": ["minecraft:iron_ingot:-1:1"]
}
````
plik ten musi się znaleźć w ```/src/meuivadditions/resources/assets/meuivadditions/jsondefs/parts```

----

tekstury dla modelu trafiają do ```/src/meuivadditions/resources/assets/meuivadditions/textures/parts```<br>
natomiast tekstury dla itemów do ```/src/meuivadditions/resources/assets/meuivadditions/textures/items/parts```

> [!WARNING]
> Wszystkie pliki powiązane z danym jsonem muszą być nazwane **identycznie**. **Jest to czułe na wielkość liter.**<br>
> np: jak JSON jest ```licence_plate_pl.json``` to tekstury muszą posiadać identyczne nazwy.

### Małe flagi do pojadów.

Szablon pliku JSON dla małych flag:
```{
  "generic": {
    "type": "generic_flag_small"
  },
  "custom": {
    "width": 0.25,
    "height": 0.25
  },
  "definitions": [
    {
      "subName": "",
      "modelName": "flag_car",
      "name": "NAZWA ITEMU",
      "extraMaterials": []
    }
  ],
  "rendering": {
    "lightObjects": [],
    "particles": [],
    "modelType": "obj"
  },
  "general": {
    "name": "NAZWA ITEMU",
    "description": "OPIS",
    "health": 100,
    "materials": ["minecraft:stick:1,minecraft:paper:2,minecraft:iron_ingot:1"]
  }
}
```

plik ten musi się znaleźć w ```/src/meuivadditions/resources/assets/meuivadditions/jsondefs/parts```

----

tekstury dla modelu trafiają do ```/src/meuivadditions/resources/assets/meuivadditions/textures/parts```<br>
natomiast tekstury dla itemów do ```/src/meuivadditions/resources/assets/meuivadditions/textures/items/parts```

> [!WARNING]
> Wszystkie pliki powiązane z danym jsonem muszą być nazwane **identycznie**. **Jest to czułe na wielkość liter.**<br>
> np: jak JSON jest ```licence_plate_pl.json``` to tekstury muszą posiadać identyczne nazwy.

### inne elementy

Coś niedziała ten słupek, muszę po kombinować z tym.

Pisz na dc jak coś.

