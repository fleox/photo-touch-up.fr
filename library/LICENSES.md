# Library — sources and licences

Bundled content of AgentPhoto (`@fleox/agentphoto`), catalogued in `index.json`
(`kb`, `width` and `height` are recomputed by `scripts/build-library.mjs`;
`--check` verifies them).

## Fonts

Static WOFF2 files taken unmodified from the Fontsource npm packages
(`@fontsource/<family>@5.1.0`, https://fontsource.org), which redistribute the
Google Fonts builds. For each weight/style two subsets are shipped, `latin` and
`latin-ext`; the engine registers both under one family with the
`unicode-range` stored in `index.json` (copied from Fontsource's CSS), so
accented characters such as é ß ő ł ş render.

| Catalog id | Family | Weights | Copyright | Licence | Upstream |
|---|---|---|---|---|---|
| `inter` | Inter | 400, 600, 700, 800 | Copyright 2020 The Inter Project Authors (Rasmus Andersson) | OFL-1.1 | https://github.com/rsms/inter |
| `montserrat` | Montserrat | 400, 700, 800 | Copyright 2024 The Montserrat Project Authors (Julieta Ulanovsky) | OFL-1.1 | https://github.com/JulietaUla/Montserrat |
| `poppins` | Poppins | 400, 600, 700 | Copyright 2020 The Poppins Project Authors (Indian Type Foundry) | OFL-1.1 | https://github.com/itfoundry/Poppins |
| `playfair` | Playfair Display | 400, 400 italic, 700 | Copyright 2017 The Playfair Display Project Authors (Claus Eggers Sørensen), with Reserved Font Name "Playfair Display" | OFL-1.1 | https://github.com/clauseggers/Playfair |
| `bebas-neue` | Bebas Neue | 400 | Copyright © 2010 by Dharma Type (Ryoichi Tsunekawa) | OFL-1.1 | https://github.com/dharmatype/Bebas-Neue |
| `anton` | Anton | 400 | Copyright 2020 The Anton Project Authors (Vernon Adams) | OFL-1.1 | https://github.com/googlefonts/AntonFont |
| `oswald` | Oswald | 400, 600 | Copyright 2016 The Oswald Project Authors (Vernon Adams, Kalapi Gajjar, Cyreal) | OFL-1.1 | https://github.com/googlefonts/OswaldFont |
| `lobster` | Lobster | 400 | Copyright 2010 The Lobster Project Authors (Pablo Impallari), with Reserved Font Name "Lobster" | OFL-1.1 | https://github.com/impallari/The-Lobster-Font |
| `pacifico` | Pacifico | 400 | Copyright 2018 The Pacifico Project Authors (Vernon Adams, Jacques Le Bailly, Botjo Nikoltchev, Ani Petrova) | OFL-1.1 | https://github.com/googlefonts/Pacifico |
| `caveat` | Caveat | 400, 700 | Copyright 2014 The Caveat Project Authors (Impallari Type) | OFL-1.1 | https://github.com/googlefonts/caveat |
| `dm-serif` | DM Serif Display | 400 | Copyright 2014-2017 Adobe Systems Incorporated, with Reserved Font Name 'Source'. Copyright 2019 Google LLC (Colophon Foundry) | OFL-1.1 | https://github.com/googlefonts/dm-fonts |
| `space-grotesk` | Space Grotesk | 500, 700 | Copyright 2020 The Space Grotesk Project Authors (Florian Karsten) | OFL-1.1 | https://github.com/floriankarsten/space-grotesk |
| `jetbrains-mono` | JetBrains Mono | 400, 700 | Copyright 2020 The JetBrains Mono Project Authors (JetBrains) | OFL-1.1 | https://github.com/JetBrains/JetBrainsMono |
| `archivo-black` | Archivo Black | 400 | Copyright 2017 The Archivo Black Project Authors (Omnibus-Type) | OFL-1.1 | https://github.com/Omnibus-Type/ArchivoBlack |
| `roboto-slab` | Roboto Slab | 400, 700 | Copyright 2018 The Roboto Slab Project Authors (Christian Robertson, Google) | **Apache-2.0** | https://github.com/googlefonts/robotoslab |

- SIL Open Font License 1.1: full text in `fonts/OFL.txt` (also
  https://openfontlicense.org). The files are shipped unmodified, bundled with
  software and never sold by themselves, as the OFL allows. Playfair Display,
  Lobster and DM Serif Display ('Source') declare Reserved Font Names: the files
  are not modified, so the original names are kept.
- Roboto Slab is distributed by Google Fonts under the Apache License 2.0 (not
  the OFL): full text in `fonts/roboto-slab/LICENSE.txt`.

## Images

Photographs originally published on Unsplash before June 2017 under CC0 1.0
(Creative Commons Zero, public-domain dedication), mirrored and licence-reviewed
on Wikimedia Commons (licence verified on each Commons file page). Resized to
1600 px on the long side and re-encoded as JPEG; metadata stripped. CC0 needs
no attribution — credits are given as a courtesy.

| Catalog id | File | Title | Author | Licence | Source |
|---|---|---|---|---|---|
| `portrait` | `images/portrait.jpg` | Portrait of a man | William Stitt | CC0-1.0 | https://commons.wikimedia.org/wiki/File:Portrait_of_a_man_(Unsplash).jpg (orig. https://unsplash.com/photos/B0m8ZIR-CF0) |
| `product` | `images/product.jpg` | Enamel coffee mug on a table | Ryan Holloway | CC0-1.0 | https://commons.wikimedia.org/wiki/File:Coffee_Mug_(Unsplash).jpg (orig. https://unsplash.com/photos/JyDmUaXMib4) |
| `pet` | `images/pet.jpg` | Furry gray cat | Kamonnat Onnom | CC0-1.0 | https://commons.wikimedia.org/wiki/File:Furry_gray_cat_(Unsplash).jpg (orig. https://unsplash.com/photos/imdkx0Ck9iY) |
| `landscape` | `images/landscape.jpg` | Mountain lake | Aleksandra Boguslawska | CC0-1.0 | https://commons.wikimedia.org/wiki/File:Mountain_lake_(Unsplash).jpg (orig. https://unsplash.com/photos/_NF9WxYgV34) |
| `city` | `images/city.jpg` | Quaint city street | Eduardo Arcos | CC0-1.0 | https://commons.wikimedia.org/wiki/File:Quaint_City_Streets_(Unsplash).jpg (orig. https://unsplash.com/photos/ZttxRsLAl7I) |
| `food` | `images/food.jpg` | Veggie burger on a plate | Markus Spiske | CC0-1.0 | https://commons.wikimedia.org/wiki/File:Veggie_burger_on_plate_(Unsplash).jpg (orig. https://unsplash.com/photos/CDbmzuFBc5E) |
