# Room Planner – Interaktivní 2D/3D plánovač podkrovního pokoje

🔗 **Živá stránka:** https://svatos-jirka.github.io/room-planner/

## Co aplikace umí

- **Interaktivní 3D náhled** pokoje (otáčení myší, zoom kolečkem, různé přednastavené pohledy)
- **Půdorys 2D** – přetahování nábytku, dveří, oken, přichytávání ke stěnám
- **Příčný řez podkrovím** s rozměry (nadezdívky, šikminy, rovný strop), které lze upravovat přímo kliknutím v obrázku nebo tažením vrcholů střechy myší
- **Správa projektů** – vytváření, přejmenování, duplikování a mazání více návrhů, vše uložené v prohlížeči (localStorage)
- **Export/Import** – stažení půdorysu a řezu jako PNG, export/import celého projektu jako JSON

## Soubory v repozitáři

| Soubor | Popis |
|---|---|
| `index.html` / `pokoj_3d_interaktivni_nahled.html` | Hlavní aplikace (stejný obsah; `index.html` slouží pro GitHub Pages) |
| `pokoj_pudorys_roomsketcher.png` | Export půdorysu z RoomSketcher |
| `pokoj_pricny_rez.png` | Export příčného řezu |
| `pokoj_pudorys.dxf` | Půdorys ve formátu DXF |
| `pokoj_3d_model.obj` | 3D model pokoje |

## Spuštění lokálně

Stačí otevřít `index.html` v prohlížeči – žádný build ani server není potřeba.
