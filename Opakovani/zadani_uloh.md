**Obecné pokyny**

Všechny úlohy zpracovávejte samostatně, snažte se nevyužívat jiné zdroje, než oficiální dokumentace. Potřebujeme zjistit úroveň, na které jste po prvním ročníku programování.

**Úloha 1: Operace s jednorozměrným polem**

**Zadání:** Napište program, který provede následující úkoly s jednorozměrným polem celých čísel:

1.  Vytvořte pole s 10 náhodně vygenerovanými celými čísly v rozmezí od 1 do 100.

2.  Vypište obsah pole.

3.  Najděte a vypište největší a nejmenší hodnotu v poli.

4.  Vypočítejte a vypište průměr všech hodnot v poli.

5.  Seřaďte pole vzestupně a vypište seřazené hodnoty.

**Komponenty:**

- Náhodná čísla (Random)

- Jednorozměrné pole

- Cyklus (for)

- Operace s polem (vyhledání minima, maxima, výpočet průměru)

- Řazení pole

**Úloha 2: Matice (dvourozměrné pole)**

**Zadání:** Napište program, který vytvoří dvourozměrné pole (matici) 5x5 a naplní ho náhodnými čísly v rozmezí od 1 do 50. Program následně:

1.  Vypíše matici v tabulkové formě.

2.  Najde a vypíše největší a nejmenší hodnotu v celé matici.

3.  Spočítá a vypíše součet všech hodnot v matici.

4.  Vypíše hlavní diagonálu (od prvního řádku a prvního sloupce po poslední řádek a poslední sloupec).

**Komponenty:**

- Dvourozměrné pole

- Náhodná čísla (Random)

- Vnořené cykly (for)

- Operace s maticí (nalezení minima, maxima, součtu)

**Úloha 3: Práce s metodami**

**Zadání:** Vytvořte program, který bude obsahovat následující metody:

1.  VytvorPole(int velikost): Vytvoří a vrátí jednorozměrné pole zadané velikosti, naplněné náhodnými čísly.

2.  VypisPole(int\[\] pole): Vypíše všechny prvky pole.

3.  NajdiMinimum(int\[\] pole): Vrátí nejmenší hodnotu v poli.

4.  NajdiMaximum(int\[\] pole): Vrátí největší hodnotu v poli.

5.  VypocitejPrumer(int\[\] pole): Vrátí průměr všech hodnot v poli.

Použijte tyto metody k vytvoření pole o velikosti 10, vypište pole, najděte a vypište jeho minimum, maximum a průměr.

**Komponenty:**

- Metody s návratovou hodnotou a parametry

- Jednorozměrné pole

- Náhodná čísla (Random)

- Operace s polem

**Úloha 4: Práce s Listem**

**Zadání:** Napište program, který:

1.  Vytvoří List\<int\> a naplní ho 20 náhodnými čísly v rozmezí od 1 do 100.

2.  Vypíše všechny hodnoty v Listu.

3.  Přidá do Listu další náhodné číslo.

4.  Odebere z Listu všechny sudé hodnoty.

5.  Vypíše finální obsah Listu.

**Komponenty:**

- List\<T\>

- Náhodná čísla (Random)

- Práce s kolekcemi (přidávání a odebírání prvků)

- Cyklus (foreach nebo for)

**Úloha 5: Použití Dictionary**

**Zadání:** Vytvořte program, který používá Dictionary\<string, int\> pro evidenci studentů a jejich známek:

1.  Přidejte 5 studentů do Dictionary, kde klíčem bude jméno studenta a hodnotou jeho známka.

2.  Vypište všechny studenty a jejich známky.

3.  Umožněte uživateli zadat jméno studenta a upravit jeho známku.

4.  Vypište aktualizovaný seznam studentů.

**Komponenty:**

- Dictionary\<TKey, TValue\>

- Práce s klíči a hodnotami

- Cyklus (foreach)

- Uživatelský vstup (Console.ReadLine())

**Úloha 6: Třída Kruh**

**Zadání:** Vytvořte třídu Kruh, která bude mít následující atributy a metody:

- **Atributy**:

  - Polomer (double) – poloměr kruhu.

- **Metody**:

  - VypocitejObvod() – vrátí obvod kruhu.

  - VypocitejObsah() – vrátí obsah kruhu. Vytvořte instanci třídy Kruh, nastavte poloměr a vypište obvod a obsah.

**Úloha 7: Evidence vozidel**

**Zadání:** Vytvořte třídu Auto, která bude obsahovat atributy jako Znacka, Model, RokVyroby a NajeteKilometry. Poté vytvořte třídu Autopark, která bude obsahovat seznam vozidel (List\<Auto\>) a metody pro přidání vozidla, odstranění vozidla a vypsání všech vozidel. Na závěr otestujte tuto funkcionalitu.

**Úloha 8: Matice a součty řádků**

**Zadání:** Napište program, který vytvoří dvourozměrné pole (matici) 4x4 naplněné náhodnými čísly. Program spočítá a vypíše součet každého řádku a najde řádek s největším součtem.

**Úloha 9: Slovní analýza s využitím Dictionary**

**Zadání:** Vytvořte program, který používá Dictionary\<char, int\> k počítání výskytu jednotlivých písmen v zadaném slově. Uživatel zadá slovo, program spočítá a vypíše, kolikrát se každé písmeno ve slově vyskytuje.

**10. souhrnná úloha: Správa knihovny**

Vytvořte program pro správu knihovny. Program bude využívat následující třídy:

1.  **Třída Kniha**:

    - **Atributy**:

      - Nazev (string) – název knihy.

      - Autor (string) – autor knihy.

      - RokVydani (int) – rok vydání knihy.

      - PocetStran (int) – počet stran knihy.

    - **Metody**:

      - VypisInformace() – vypíše informace o knize včetně názvu, autora, roku vydání a počtu stran.

2.  **Třída Knihovna**:

    - **Atributy**:

      - Nazev (string) – název knihovny.

      - Knihy (List\<Kniha\>) – seznam knih v knihovně.

    - **Metody**:

      - PridejKnihu(Kniha kniha) – přidá knihu do seznamu knih.

      - OdeberKnihu(string nazev) – odebere knihu podle názvu.

      - VypisVsechnyKnihy() – vypíše všechny knihy v knihovně.

      - NajdiKnihuPodleNazvu(string nazev) – vyhledá a vrátí knihu podle názvu.

      - VypisKnihyOdAutora(string autor) – vypíše všechny knihy od zadaného autora.

3.  **Třída Program**:

    - **Popis**:

      - Program bude obsahovat hlavní metodu, která bude interagovat s uživatelem a umožní mu provádět operace, jako je přidání knihy, odebrání knihy, vyhledání knihy podle názvu, vyhledání knih podle autora, a zobrazení všech knih v knihovně.

**Požadavky:**

- **Přidání knihy**: Uživatel zadá název, autora, rok vydání a počet stran. Tyto informace se uloží jako nová instance třídy Kniha a přidají se do seznamu knih v knihovně.

- **Odebrání knihy**: Uživatel zadá název knihy, která má být odstraněna ze seznamu.

- **Vyhledání knihy podle názvu**: Uživatel zadá název knihy, kterou chce vyhledat. Program vypíše informace o této knize, pokud je nalezena.

- **Zobrazení knih od určitého autora**: Uživatel zadá jméno autora a program vypíše všechny knihy od tohoto autora, které se nachází v knihovně.

- **Zobrazení všech knih**: Program vypíše seznam všech knih v knihovně, včetně jejich detailů.

**Dodatečné požadavky**:

- Program by měl být schopen pracovat s minimálně 10 různými knihami.

- Uživatel by měl mít možnost opakovaně zadávat příkazy, dokud nezvolí možnost ukončení programu.
