<img align="right" width="150" height="150" src="spojentetitlogo.svg?raw=true">

**SpojeNetIT s.r.o.** is a Czech communications company that publishes part of its software to be available to all who use it.

Take a look at our resources and decide for yourself whether it would be more advantageous for you to order deployment and configuration from us as a paid service.

### Our products matrix

| Bank | PHP Library | Statement Tools | Pohoda Importer | AbraFlexi Importer |
| ---- | ----------- | --------------- | --------------- | ------------------ |
| [Fio](https://www.fio.cz/) | | [fiobank-statement-tools](https://github.com/Spoje-NET/fiobank-statement-tools) | | |
| [Raiffeisen Bank](https://www.rb.cz/) | [rbczpremiumapi](https://github.com/VitexSoftware/php-vitexsoftware-rbczpremiumapi) | [raiffeisenbank-statement-tools](https://github.com/Spoje-NET/raiffeisenbank-statement-tools) | [pohoda-raiffeisenbank](https://github.com/Spoje-NET/pohoda-raiffeisenbank) | [abraflexi-raiffeisenbank](https://github.com/VitexSoftware/abraflexi-raiffeisenbank) |
| [Česká Spořitelna a.s.](https://www.csas.cz/) | [csas-accountsapi](https://github.com/Spoje-NET/php-csas-accountsapi) | | [csas-pohoda](https://github.com/Spoje-NET/csas-pohoda) / [pohoda-csas](https://github.com/Spoje-NET/pohoda-csas) | |
| [Komerční Banka a.s.](https://www.kb.cz/) | [kb-accountsapi](https://github.com/Spoje-NET/php-kb-accountsapi) | [kb-statement-tools](https://github.com/Spoje-NET/kb-statement-tools) | [pohoda-kb](https://github.com/Spoje-NET/pohoda-kb) | |

#### for AbraFlexi ![AbraFlexi](abraflexi.svg?raw=true)

* [php-abraflexi](https://github.com/Spoje-NET/php-abraflexi) — PHP Library for easy interaction with economic system AbraFlexi
* [Discomp to Abraflexi](https://github.com/Spoje-NET/discomp2abraflexi) — Import Discomp pricelist into AbraFlexi
* [AbraFlexi IPEX](https://github.com/Spoje-NET/abraflexi-ipex) — Ipex ⑂ AbraFlexi integration
* [Subreg to AbraFlexi](https://github.com/Spoje-NET/subreg2abraflexi) — Import Subreg Pricelist into AbraFlexi

#### for Pohoda ![Stormware Pohoda](pohoda.svg?raw=true)

**Core / platform**

* [PohodaSQL](https://github.com/Spoje-NET/PohodaSQL) — PHP library for Pohoda SQL tables (`DatSave`, agendas FA/BV/AD, …)
* [pohoda-changes-api](https://github.com/Spoje-NET/pohoda-changes-api) — Change poller (mServer `lastChanges` or MSSQL `DatSave`), MultiFlexi-compatible `record_cache` / `changes_cache`, outbound webhooks
* [pohoda-tools](https://github.com/Spoje-NET/pohoda-tools) — CLI helpers for mServer (e.g. fake bank receipts for poller tests), analogous to AbraFlexi-Tools
* [pohoda-client-checker](https://github.com/Spoje-NET/pohoda-client-checker) — Check connection to Stormware mServer
* [pohodactl](https://github.com/Spoje-NET/pohodactl) — Enhanced PowerShell automation for STORMWARE POHODA
* [pohoda](https://github.com/Spoje-NET/pohoda) — XML generator and parser for Pohoda

**Bank statement importers**

* [pohoda-raiffeisenbank](https://github.com/Spoje-NET/pohoda-raiffeisenbank) — Import Raiffeisenbank statements into Pohoda
* [pohoda-kb](https://github.com/Spoje-NET/pohoda-kb) — Import Komerční Banka statements into Pohoda
* [pohoda-csas](https://github.com/Spoje-NET/pohoda-csas) / [csas-pohoda](https://github.com/Spoje-NET/csas-pohoda) — Import Česká Spořitelna statements into Pohoda
* [pohoda-csob](https://github.com/Spoje-NET/pohoda-csob) — Import ČSOB statements and movements into Pohoda
* [pohoda-unicredit](https://github.com/Spoje-NET/pohoda-unicredit) — Import UniCredit statements and movements into Pohoda
* [pohoda-abo-importer](https://github.com/Spoje-NET/pohoda-abo-importer) — Import ABO statements into Pohoda via mServer

**Other importers / integrations**

* [pohoda-asset-tools](https://github.com/Spoje-NET/pohoda-asset-tools) — Import fixed assets (majetek) into Pohoda from an XLSX spreadsheet
* [Pohoda to Realpad](https://github.com/Spoje-NET/pohoda-realpad) — Pohoda ↔ Realpad integration tools

#### for Realpad ![Realpad Logo](realpad.svg?raw=true)

* [Pohoda to Realpad](https://github.com/Spoje-NET/pohoda-realpad) — Pohoda ↔ Realpad integration tools
* [Realpad to Mailkit](https://github.com/Spoje-NET/realpad2mailkit) — Synchronize Realpad contacts into Mailkit
* [Takeout Library](https://github.com/Spoje-NET/PHP-Realpad-Takeout) — Realpad Takeout API client for backups
