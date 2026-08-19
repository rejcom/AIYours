# AIYours

AI nad označeným textem. Lokálně. Bez cloudu.

AIYours je Windows aplikace, která běží v system tray a dává vám okamžitý přístup k lokálnímu AI modelu — bez posílání jakýchkoliv dat na internet. Celá inference běží přímo na vašem počítači.

## Co umí

- **Rychlé AI akce nad označeným textem** — označte text kdekoliv ve Windows (prohlížeč, Word, poznámkový blok...), stiskněte `Ctrl+Shift+A` a vyberte akci:
  - Opravit gramatiku a pravopis
  - Přeložit → EN / Přeložit → CZ
  - Zkrátit
  - Přepsat profesionálně
  - Anonymizovat (najde a zamaskuje jméno, adresu, rodné číslo, telefon, email...)
  - Vlastní instrukce
- **Analýza dokumentů** — nahrajte PDF nebo fotku/sken, OCR rozpozná text (i vícestránkové dokumenty), a nad výsledkem můžete spustit stejné AI akce. Hodí se hlavně pro anonymizaci citlivých naskenovaných dokumentů.
- **Vše offline** — model běží lokálně přes llama.cpp, žádná data neopouští zařízení. Internet je potřeba jen jednou, při prvním spuštění, na stažení modelu.
- **Setup wizard** — při prvním spuštění změří výkon vašeho počítače a doporučí odpovídající velikost modelu (rychlejší/menší vs. kvalitnější/větší).

## Stažení

Aktuální verzi najdete na [stránce Releases](../../releases/latest). Stáhněte si `.exe` podle procesoru vašeho počítače:

| Soubor | Pro koho |
|---|---|
| `AIYours-x64.exe` | drtivá většina PC a notebooků (Intel/AMD) |
| `AIYours-ARM64.exe` | Windows on ARM (např. Snapdragon X Elite) |

Nejste si jistí? Zjistíte v **Nastavení → Systém → O systému → Typ systému**. `AIYours-x64.exe` navíc běží i emulovaně na ARM, takže funguje skoro vždy.

## Spuštění

Žádná instalace. Stáhněte si `.exe`, spusťte ho, appka naskočí do system tray. Při prvním spuštění vás provede průvodce výběrem a stažením AI modelu (jednorázově potřeba internet). Poté funguje appka čistě offline.

## Poznámka

Jde o osobní projekt. Zdrojový kód zatím není veřejný — v repozitáři jsou jen hotové sestavené verze ke stažení.
