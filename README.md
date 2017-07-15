Om projektet
============
Projektet går ut på att skapa ett bibliotek över de vanligast symbolerna som krävs för att rita elscheman. Målet är att i största möjliga mån vara kompatibel med IEC 60617.



Symboler
========
Nedan följer en lista över samtliga 21st symboler som finns i biblioteket.

Bild                                                | Filnamn                           | Bredd | Höjd | Beskrivning
----------------------------------------------------|-----------------------------------|-------|------|----------------------------
![thumb](Symbols/Motor_1ph.svg)                     | Motor_1ph.svg                     |   400 |  300 | Motor 1-fas
![thumb](Symbols/Relay_coil.svg)                    | Relay_coil.svg                    |   200 |  300 | Spole till relä / kontaktor
![thumb](Symbols/Switch_no.svg)                     | Switch_no.svg                     |   200 |  100 | Relä (NO)
![thumb](Symbols/Switch_nc.svg)                     | Switch_nc.svg                     |   200 |  100 | Relä (NC)
![thumb](Symbols/Switch_contactor.svg)              | Switch_contactor.svg              |   200 |  100 | Kontaktor (NO)
![thumb](Symbols/Switch_mushroom_momentary_no.svg)  | Switch_mushroom_momentary_no.svg  |   200 |  150 | Svampströmbrytare momentan (NO)
![thumb](Symbols/Switch_mushroom_momentary_nc.svg)  | Switch_mushroom_momentary_nc.svg  |   200 |  150 | Svampströmbrytare momentan (NC)
![thumb](Symbols/Switch_mushroom_latch_no.svg)      | Switch_mushroom_latch_no.svg      |   200 |  150 | Svampströmbrytare självlåsande
![thumb](Symbols/Switch_mushroom_latch_nc.svg)      | Switch_mushroom_latch_nc.svg      |   200 |  150 | Svampströmbrytare självlåsande
![thumb](Symbols/Switch_mushroom_twistlatch_no.svg) | Switch_mushroom_twistlatch_no.svg |   200 |  200 | Svampströmbrytare självlåsande med vridåterställning
![thumb](Symbols/Switch_mushroom_twistlatch_nc.svg) | Switch_mushroom_twistlatch_nc.svg |   200 |  200 | Svampströmbrytare självlåsande med vridåterställning
![thumb](Symbols/Switch_push_no.svg)                | Switch_push_no.svg                |   200 |  150 | Tryckknapp återfjädrande (NO)
![thumb](Symbols/Switch_push_nc.svg)                | Switch_push_nc.svg                |   200 |  150 | Tryckknapp återfjädrande (NC)
![thumb](Symbols/Switch_rot_no.svg)                 | Switch_rot_no.svg                 |   200 |  150 | Vridströmställare (NO)
![thumb](Symbols/Switch_rot_nc.svg)                 | Switch_rot_nc.svg                 |   200 |  150 | Vridströmställare (NC)
![thumb](Symbols/Lightbulb.svg)                     | Lightbulb.svg                     |   200 |  200 | Glödlampa
![thumb](Symbols/Transformer_3ph_delta_star.svg)    | Transformer_3ph_delta_star.svg    |   350 |  350 | 3-fas transformator delta/Y-kopplad
![thumb](Symbols/Circuit_breaker.svg)               | Circuit_breaker.svg               |   250 |  100 | Automatsäkring (Dvärgbrytare)
![thumb](Symbols/Dot.png)                           | Dot.png                           |   100 |  100 | Punkt för att förbinda ledningar
![thumb](Symbols/Not_connected.svg)                 | Not_connected.svg                 |   100 |  100 | Ej ansluten ledare (Kryss)
![thumb](Symbols/PE.svg)                            | PE.svg                            |   100 |  100 | Skyddsjord



Symboler todo
=============
Lista över symboler som håller på ritas eller är i behov av ändringar

Bild                                                | Filnamn                           | Bredd | Höjd | Beskrivning
----------------------------------------------------|-----------------------------------|-------|------|----------------------------
![thumb](Symbols/Switch_key_no.svg)                 | Switch_key_no.svg                 |   200 |  150 | Rita: Nyckelströmställare (NO)
![thumb](Symbols/Switch_key_nc.svg)                 | Switch_key_nc.svg                 |   200 |  150 | Rita: Nyckelströmställare (NC)
![thumb](Symbols/Motor_3ph.svg)                     | Motor_3ph.svg                     |   400 |  300 | Rita: Rita
![thumb](Symbols/Transformer_1ph.svg)               | Transformer_1ph.svg               |   350 |  350 | Rita: Vanlig transformator
![thumb](Symbols/A4.svg)                            | A4.svg                            |   xxx |  xxx | Rita: Dokumentmall A4
![thumb](Symbols/Motor_1ph.svg)                     | Motor_1ph.svg                     |       |      | Todo: Förminska?
![thumb](Symbols/Circuit_breaker.svg)               | Circuit_breaker.svg               |       |      | Todo: Skulle behöva snyggas till så de passar att stacka på varandra, eller rita en ny symbol för 2-pol / 3-pol



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