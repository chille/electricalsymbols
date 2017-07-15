Om projektet
============
Projektet går ut på att skapa ett bibliotek över de vanligast symbolerna som krävs för att rita elscheman. Målet är att i största möjliga mån vara kompatibel med IEC 60617.



Symboler
========
Nedan följer en lista över samtliga 21st symboler som finns i biblioteket.

Bild                                                                                           | Filnamn                           | Bredd | Höjd | Beskrivning
-----------------------------------------------------------------------------------------------|-----------------------------------|-------|------|----------------------------
![missing thumb](https://chille.github.io/electricalsymbols/Motor_1ph.svg)                     | Motor_1ph.svg                     |   400 |  300 | Motor 1-fas
![missing thumb](https://chille.github.io/electricalsymbols/Relay_coil.svg)                    | Relay_coil.svg                    |   200 |  300 | Spole till relä / kontaktor
![missing thumb](https://chille.github.io/electricalsymbols/Switch_no.svg)                     | Switch_no.svg                     |   200 |  100 | Relä (NO)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_nc.svg)                     | Switch_nc.svg                     |   200 |  100 | Relä (NC)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_contactor.svg)              | Switch_contactor.svg              |   200 |  100 | Kontaktor (NO)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_mushroom_momentary_no.svg)  | Switch_mushroom_momentary_no.svg  |   200 |  150 | Svampströmbrytare momentan (NO)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_mushroom_momentary_nc.svg)  | Switch_mushroom_momentary_nc.svg  |   200 |  150 | Svampströmbrytare momentan (NC)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_mushroom_latch_no.svg)      | Switch_mushroom_latch_no.svg      |   200 |  150 | Svampströmbrytare självlåsande
![missing thumb](https://chille.github.io/electricalsymbols/Switch_mushroom_latch_nc.svg)      | Switch_mushroom_latch_nc.svg      |   200 |  150 | Svampströmbrytare självlåsande
![missing thumb](https://chille.github.io/electricalsymbols/Switch_mushroom_twistlatch_no.svg) | Switch_mushroom_twistlatch_no.svg |   200 |  200 | Svampströmbrytare självlåsande med vridåterställning
![missing thumb](https://chille.github.io/electricalsymbols/Switch_mushroom_twistlatch_nc.svg) | Switch_mushroom_twistlatch_nc.svg |   200 |  200 | Svampströmbrytare självlåsande med vridåterställning
![missing thumb](https://chille.github.io/electricalsymbols/Switch_push_no.svg)                | Switch_push_no.svg                |   200 |  150 | Tryckknapp återfjädrande (NO)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_push_nc.svg)                | Switch_push_nc.svg                |   200 |  150 | Tryckknapp återfjädrande (NC)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_rot_no.svg)                 | Switch_rot_no.svg                 |   200 |  150 | Vridströmställare (NO)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_rot_nc.svg)                 | Switch_rot_nc.svg                 |   200 |  150 | Vridströmställare (NC)
![missing thumb](https://chille.github.io/electricalsymbols/Lightbulb.svg)                     | Lightbulb.svg                     |   200 |  200 | Glödlampa
![missing thumb](https://chille.github.io/electricalsymbols/Transformer_3ph_delta_star.svg)    | Transformer_3ph_delta_star.svg    |   350 |  350 | 3-fas transformator delta/Y-kopplad
![missing thumb](https://chille.github.io/electricalsymbols/Circuit_breaker.svg)               | Circuit_breaker.svg               |   250 |  100 | Automatsäkring (Dvärgbrytare)
![missing thumb](https://chille.github.io/electricalsymbols/Dot.svg)                           | Dot.png                           |   100 |  100 | Punkt för att förbinda ledningar
![missing thumb](https://chille.github.io/electricalsymbols/Not_connected.svg)                 | Not_connected.svg                 |   100 |  100 | Ej ansluten ledare (Kryss)
![missing thumb](https://chille.github.io/electricalsymbols/PE.svg)                            | PE.svg                            |   100 |  100 | Skyddsjord



Symboler todo
=============
Lista över symboler som håller på ritas eller är i behov av ändringar

Bild                                                                                           | Filnamn                           | Bredd | Höjd | Beskrivning
-----------------------------------------------------------------------------------------------|-----------------------------------|-------|------|----------------------------
![missing thumb](https://chille.github.io/electricalsymbols/Switch_key_no.svg)                 | Switch_key_no.svg                 |   200 |  150 | Rita: Nyckelströmställare (NO)
![missing thumb](https://chille.github.io/electricalsymbols/Switch_key_nc.svg)                 | Switch_key_nc.svg                 |   200 |  150 | Rita: Nyckelströmställare (NC)
![missing thumb](https://chille.github.io/electricalsymbols/Motor_3ph.svg)                     | Motor_3ph.svg                     |   400 |  300 | Rita: Rita
![missing thumb](https://chille.github.io/electricalsymbols/Transformer_1ph.svg)               | Transformer_1ph.svg               |   350 |  350 | Rita: Vanlig transformator
![missing thumb](https://chille.github.io/electricalsymbols/A4.svg)                            | A4.svg                            |   xxx |  xxx | Rita: Dokumentmall A4
![missing thumb](https://chille.github.io/electricalsymbols/Motor_1ph.svg)                     | Motor_1ph.svg                     |       |      | Todo: Förminska?
![missing thumb](https://chille.github.io/electricalsymbols/Circuit_breaker.svg)               | Circuit_breaker.svg               |       |      | Todo: Skulle behöva snyggas till så de passar att stacka på varandra, eller rita en ny symbol för 2-pol / 3-pol



Design guidlines
================
* Alla symboler ritas i Inkscape och sparas i mappen Symbols/
* Alla *.svg i "Units: px"
* Gridstorlek på 50x50 px (5x5px major grid lines every 10)
* Storleken på bilden skall gå jämt ut med grid
* Placering av anslutningar skall ligga på grid
* Marginal på cirka 50px på de sidor som saknar anslutning (Så att allting garanterat får plats innuti bilden och inte beskärs)
* Mindre detaljer kan avvika från grid
* Metainformation om symbolen lagras i ovanstående tabellen i README.md
* Bidrag till projektet skickas i första hand som en pull request på GitHub. Om någon inte är bekant med Git skickas filerna till mig (eller någon annan) som lägger in dem.
* TODO: Bestämma font för text + textstorlekar
* TODO: Bestäm riktlinjer för sträckade linjer



Framtida projekt
================
* Symboler exporteras (med hjälp av ett script) till en minimalistisk *.svg som läggs i Symbols2/
* Mer omfattande databas med metainformation för filerna (XML, JSON, etc)
* I framtiden finns det potential att bygga vidare på detta projekt. Till exempel vore det inte en dum ide att bygga ett superenkelt webbaserad CAD-program med möjlighet att lagra ritningar online och exportera SVG och/eller PDF.



Copyright and licensing
=======================
Copyright © 2017 Christian Antila. All rights reserved

All material in this repository is released under the Creative Commons license, CC BY-SA 3.0

https://creativecommons.org/licenses/by-sa/3.0/



Changelog
=========
TBD