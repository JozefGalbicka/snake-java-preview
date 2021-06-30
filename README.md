# snake-game-preview
<p align="center">
  <img width=500, src="https://user-images.githubusercontent.com/86607609/123657417-0d1e0380-d831-11eb-9c07-390f678bd289.png" />
</p>

<p align="center">
  Simple Snake game made for a college assignment using Java.
</p>

Note: Project documentation and code itself (class/method names) were written in Slovak language.

Original description in Slovak language:

Hra snake bola navrhnutá a naprogramovaná v rovnakej forme, v akej je vo väčšine prípadoch verejne dostupná(hra sa spúšťa pomocou skriptu play.cmd). To znamená, že všetky známe pravidlá zostávajú nezmenené. Hrá sa teda na predom určenej mape zloženej z dvojrozmerného poľa štvorcov, na ktorej sa pohybuje had. Zmena smeru pohybu hada sa uskutočňuje na klávesnici pomocou šípok. Mapa je ohraničená, poprípade sa na nej nachádzajú prekážky, ktoré sú reprezentované sivou farbou. V prípade, že had narazí na hranicu mapy, respektíve do prekážky, hra sa ukončí a had zmení svoju farbu na červenú. Na mape sa nachádza vždy jedno jablko(reprezentované žltou farbou), po ktorého zjedení sa had automaticky zväčší, čoho následkom je taktiež náhodné vygenerovanie ďalšieho jablka. Po zjedení všetkých jabĺk(respektíve keď had zaplní celú mapu svojim telom a nezostane žiadne voľné miesto) sa hra automaticky ukončí a had zmení svoju farbu na žlto. Zakaždým, keď hra skončí, ju je možné reštartovať stlačením klávesy medzerník.
	
  Súčasťou hry je ovládací panel, na ktorom je možné meniť nastavenia hry, a ktorý zároveň zobrazuje dosiahnuté skóre. Prvým ovládacím prvkom je obtiažnosť hry, ktorá je schopná dosahovať tri stavy – a to „EASY“, „NORMAL“ a „HARD“. Obtiažnosť hry sa mení kliknutím na prislúchajúce tlačidlo na ovládacom paneli. Hra povoľuje meniť tento prvok iba za podmienky, že hra práve nebeží. Obtiažnosť určuje, akou rýchlosťou sa bude had po mape pohybovať – t.j. čím ťažšia obtiažnosť, tým rýchlejšie sa bude had pohybovať. Obtiažnosť taktiež určuje, aké skóre had získa za zjedenie jablka. Natívne je bodovanie nastavené na nasledujúce hodnoty – „EASY“: 1 bod, „NORMAL“: 2 body, „HARD“: 3 body za jedno jablko. Ďalším ovládacím prvkom je tlačidlo na zmenu mapy. To mení aktuálnu mapu, na ktorej sa bude had pohybovať. Hra nepovoľuje zmenu mapy za behu hry. Hra obsahuje presne 4 mapy, pričom každá mapa sa líši rozložením jednotlivých prekážok(posledná mapa neobsahuje žiadne prekážky, v prípade, že si chce hráč zahrať hru bez tohto prvku). Ďalej ovládací panel obsahuje dva číselné displeje, ktoré zobrazujú dosiahnuté skóre. Prvý, ktorý sa nachádza v ľavej časti panelu(„SCORE“) zobrazuje dosiahnuté skóre za aktuálnu hru. Toto skóre sa nezobrazuje za behu hry, ale naopak, zobrazí sa až po náraze/výhre hada. Displej, ktorý sa nachádza napravo od prvého displeja(„BEST“) zobrazuje doteraz najlepšie dosiahnuté skóre od spustenia hry, ktoré hráč získal. 
