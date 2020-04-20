# Boxes of Rum
![Úvodní obrázek](/assets/img/thumb.jpg)
**Grafické podklady, veškeré změny a návrhy lze nalézt na [tomto odkazu!](https://www.figma.com/file/SNWwj8H8iW03R6Cd8TMgK4/WEB_game_app?node-id=18%3A118)**
## Pomoz pirátům přežít dlouhé dny na moři
Aby pirátům při plavbách nevyschlo v krku, potřebují rum. Jako jejich dodavatel musíš poslat na specifické souřadnice v moři bedny s rumem. Piráti souřadnice však neustále mění, aby je konfederace nenašla dřív. Dokážeš všechy bedny umístit na správné souřadnice?
## Cíl hry
Cílem hráče je umístit jednotlivé hrací panely různých tvarů do čtvercové sítě 5×5.
Hráč může být omezen pozicí beden na jednotlivých polích hrací sítě.
## Pravidla hry
1. Vyber si úroveň obtížnosti daných souřadnic.
2. Podle souřadnic správně do hrací sítě umísti hrací součásti.
3. Dej si pozor, ať jsou bedny na správném místě.
4. A máš hotovo!
## Hrací pole
Hrací pole tvoří čtvercová síť 5×5 představující moře, po kterém se piráti brázdí.
Pole je ohraničeno pobřezními bloky, odkud hráš vyráží na piráty určená místa vyložit bednu rumu.
Po vygenerování hrací plochy bude hráči poskytnuto 5 hracích panelů které budou složeny z jednotlivých herních polí.
![Potenciální poskytnité tvary](/assets/img/p_shapes.jpg)
Hráč po se bude po vygenerování sítě bude muset řídit dle označení "X". Tam mají být bedny s rumem umístěny. Pokud mu nějaké bedny přebývají, nevadí, podstatné je, aby na polích s "X" byla bedna.
## Hrací bloky
![1 pole hrací sítě před začátkem hry](/assets/graphics/still_water.svg)
![Pobřežní pole](/assets/graphics/coast.svg)
![Rohové pobřežní pole](/assets/graphics/coast_corner.svg)
![Pole s "X"](/assets/graphics/box_place.svg)
![Hrací pole s bednou](/assets/graphics/box_water.svg)
![Běžné herní pole](/assets/graphics/top_water.svg)
## Fungování aplikace
Po otevření aplikace budou uživateli představena pravidla.
![Obrazovka pravidel](/assets/img/rules.jpg)
Po přečtení pravidel bude mít na výběr jednu ze 4 obtížností, alternativa obtížností, rozestavení mapy, poloha a tvar hracích bloků dostupná ve figma návrhu na stránce **difficulty_boards**.
![Obrazovka výběru obtížnosti](/assets/img/difficulty.jpg)
Po spuštění tlačítkem HRÁT bude uživateli vyobrazena hrací plocha s označenými kříži a dostupnými hracími bloky, které bude muset uživatel do hrací plochy umístit tak, aby pozice beden odpovídali pozici křížů.
![Herní obrazovka](/assets/img/screen.jpg)
Bloky budou předem složené a natočené do pozice, ve které se mají nacházet ve správném rešení pro usnadnění realizace a hry samotné.
Veškeré herní bloky lze nalézt v pravém vyskakovacím menu (v mobilní verzi ve spodní části obrazovky).
![Bloky](/assets/img/part_choise_screen.jpg)
Na levé stránce obrazovky (v mobilní verzi v horní části), se náchází menu s možnostmi zobrazení **pravidel** a možnost **změny obtížnosti**.
![Menu](/assets/img/main_menu_screen.jpg)
Po správném umístění veškerých hracích bloků, bude uživateli vyobrazeno oznámení správného řešení, odkud má možnost HRÁT ZNOVU. Pokud se rozhodně hrát znovu, bude mu vyobrazena obrazovka s výběrem obtížnosti, načež může hrát od začátku.
![Obrazovka výhry](/assets/img/win_screen.jpg)
Pokud hráč umístí bloky nesprávně, bude mu vaobrazeno oznámení špatného řešení, odkud bude mít možnost zkusit tu samou obtížnost znovu a dosáhnout tak úspěšného řešení. Má také možnost změnit obtížnost.
![Obrazovka prohry](/assets/img/lose_screen.jpg)