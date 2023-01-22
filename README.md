# Power_BI_project

Vypracování projektu v rámci kurzu datové akademie od společnosti Engeto.

Finální PBI soubor obsahuje vizualizaci dat o úmrtí v České republice od roku 2006 do roku 2021 podle jednotlivých krajů, okresů, roků a pohlaví.

Veškerá data pochází s portálu data.gov.cz

Datové zdroje:
Tabulka Data - data o úmrtí podle okresů a podle roků
Tabulka Ciselnikkresu - číselník okresů a krajů
Tabulka pohlavi - číselník pohlaví

Propojení jednotlivých zdrojů je možné vidět v záložce Model.

Finální rozsah projektu je na 2 stránky.

Pro vizualizaci byly použity následující typy vizuálů: Karta, Karta s více řádky, Měřidlo, Výsečový graf, Spojnicový graf, Skupinový sloupcový graf, Mapa stromové struktury a Matice.


Na první stránce projektu je filtrace pomocí krajů a roků. Na druhé stránce je ještě navíc slicer na pohlaví.

V projektu jsou bookmarks použity pro vynulování filtrů na jednotlivých stránkách.

Page navigation je vytvořena pomocí červených tlačítek v horní liště (Detail a Přehled)

Datová hierarchie je vytvořena pro kraje a okresy na první stránce v zobrazení počtu úmrtí podle krajů a okresů.

V souboru je vytvořena míra , která zobrazuje celkový počet úmrtí za celé období bez jakékoliv filtrace a tato hodnota je stála bez vazby na filtraci.


V tabulce Data jsem si vytvořil kalkulovaný sloupce kategorie bez kódu, kde jsem ze sloupce kategorie odebral kód v závorce, abych zkrátil názvem pro lepší zobrazení ve vizuálu.

V tabulce CiselnikOkresu jsem si vytvořil pro zajímavost kalkulovaný sloupec kód kraj ze sloupce Kód NUTS4 okresu.

 
