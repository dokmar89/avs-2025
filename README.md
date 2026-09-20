# Služba ověřování věku — integrační zdrojový kód

Kód služby pro ověřování věku s backendem Express, zdroji rozhraní prohlížeče a příklady napojení v Node.js a PHP.

**Stav:** Starší integrační/referenční projekt. Původní zmínky o Go.cam nedokládají certifikaci tohoto repozitáře ani jeho vlastníka.

## Co projekt obsahuje

- Serverový zdroj v TypeScriptu a generované soubory JavaScriptu.
- Šablony Twig, Sass a zdroje pro sestavení klientské části.
- Příklady integrace přes iframe a přesměrování v Node.js a PHP.
- Skripty Gulp pro sestavení a sledování změn; notebooky pro měření.

## Technologie

TypeScript, Express, Twig.

## Architektura a struktura

- `source/backend/app/` — zdroj serverové části
- `source/frontend/` — zdroj klientské části a stylů
- `app/` — sestavená aplikace a šablony
- `script/gulpfile.js` — postup sestavení
- `example/` — integrační příklady
- `LICENSE` — stávající licenční podmínky

## Lokální vývoj

Potřebujete Node.js a npm. Balíček deklaruje:

```sh
npm install
npm run build
npm run startDev
```

`npm run startProd` spouští sestavenou serverovou část; `npm run watch` spouští sledování změn přes Gulp. Postup je v `script/gulpfile.js`. Před spuštěním ověřte dostupnost nástrojů a konfiguraci serveru. Příkazy nebyly při této dokumentační úpravě provedeny.

## Konfigurace a omezení

Před testem ověřte konfiguraci serveru a externí služby. Původní README odkazovalo na Go.cam a certifikace třetích stran; tyto odkazy nejsou důkazem certifikace této kopie ani jejího zcela původního autorství. Generované soubory jsou vedle zdrojů, proto před změnami ověřte postup sestavení.

## Přínos pro portfolio

Reference pro pochopení webových integrací a klientských příkladů v JavaScriptu a PHP. Při prezentaci odlišujte převzatý kód od vlastních úprav.

## Co doplnit do dokumentace

Snímky obrazovky s fiktivními daty, opakovatelný postup ověření a přehled skutečně otestovaných integrací. Přihlašovací údaje a konfigurace konkrétního nasazení patří mimo Git.
