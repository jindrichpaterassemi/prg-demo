# PRG – ukázkové soubory k výkladu

Minimalistické HTML/CSS soubory, které vidíte na projektoru v hodinách
Programování (PRG) IT2 na SŠEMI. Stáhněte si je a zkoušejte totéž, co učitel.

## Jak si to stáhnout

1. Nahoře klikněte na zelené tlačítko **Code → Download ZIP**
   (nebo přímo: `archive/refs/heads/main.zip` u tohoto repozitáře).
2. ZIP rozbalte, třeba do `Dokumenty\prg-demo`.
3. Soubor `.html` otevřete poklepáním – otevře se v prohlížeči.
   Vedle si otevřete tentýž soubor v editoru (VS Code, Poznámkový blok).
4. V prohlížeči stiskněte **F12** (nástroje vývojáře), záložky **Elements**
   a **Styles**. Po každé změně v editoru uložte a v prohlížeči dejte **F5**.

Soubory jsou schválně malé a v některých je **chyba naschvál** – je to napsané
v komentářích nebo přímo v textu stránky.

## Co je v které složce

| Složka / soubor | Téma |
|---|---|
| `demo_prg08/` | říjen 2026: DOM, kostra stránky, sémantika, cesty, CSS pravidlo, specificita, dědičnost |

### demo_prg08 (výklad PRG-08, 20. 10. 2026)

| Soubor | Co ukazuje |
|---|---|
| `demo1_spatne.html`, `demo1_dobre.html` | dvě stránky, které vypadají stejně; jedna je napsaná špatně (b, br, div), druhá správně (h1, nav, footer) |
| `demo1_rozcvicka.html` | deset dvojic „funguje, ale je to špatně“ / správně, s vysvětlením pod „Proč“ |
| `demo2_dom.html` | zdrojový kód (Ctrl+U) vs. strom v paměti (F12 → Elements) |
| `demo3_kostra.html` | kostra dokumentu: doctype, head, charset, title; co se stane, když něco smažete nebo přepíšete |
| `demo3_cp1250.html` | soubor uložený ve Windows-1250, meta tvrdí utf-8 → rozsypané háčky |
| `demo4_semantika.html` | header, nav, main, article, aside, footer s barevnými rámečky |
| `demo5_cesty/` | relativní cesty: `index.html`, `clanky/prvni.html`, `../obrazky/logo.svg`, schválně rozbité cesty |
| `demo6_pravidlo.html` | CSS pravidla s pěti druhy chyb; v F12 → Styles jsou přeškrtnutá |
| `demo7_specificita.html` | pět pravidel na jeden odkaz; které vyhraje a proč |
| `demo8_dedicnost.html` | co se dědí z body a co ne; px vs. rem vs. em |

Soubory nic neodesílají a nepotřebují internet.
