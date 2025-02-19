```
██╗░░░██╗████████╗██╗░░██╗░█████╗░
██║░░░██║╚══██╔══╝╚██╗██╔╝██╔══██╗
██║░░░██║░░░██║░░░░╚███╔╝░██║░░██║
██║░░░██║░░░██║░░░░██╔██╗░██║░░██║
╚██████╔╝░░░██║░░░██╔╝╚██╗╚█████╔╝
░╚═════╝░░░░╚═╝░░░╚═╝░░╚═╝░╚════╝░
```

> Otevřená komunitní kryptoměnová konference

[![Test, build, deploy](https://github.com/gweicz/utxo/actions/workflows/deploy.yml/badge.svg)](https://github.com/gweicz/utxo/actions/workflows/deploy.yml)

Tento repozitář obsahuje základní specifikace (datové zdroje) všech ročníků
konference.

Veškeré informace o konferenci naleznete na
[docs.utxo.cz](https://docs.utxo.cz).

## Specifikace

- Zdrojové soubory ve formátu [YAML](https://yaml.org/) jsou umístěny v adresáři
  [`spec`](./spec).
- Validační schéma ([JSON Schema](https://json-schema.org/)) najdete v adresáři
  [`utils/schema`](./utils/schema)

Jako runtime se využívá Javascriptové [Deno](https://deno.land/).

## Ročníky

| Ročník | Název       | Datum konání | Místo               |
| ------ | ----------- | ------------ | ------------------- |
| 22     | **UTXO.22** | 4.-5.6.2022  | Gabriel Loci, Praha |

## HTTP Endpoint

Veřejný HTTP endpoint s datovými soubory ve formátu JSON naleznete na adrese:

- [https://spec.utxo.cz/](https://spec.utxo.cz/)

## Datové sady

|              | Popis                                       | Ročník 2022                                                                    |
| ------------ | ------------------------------------------- | ------------------------------------------------------------------------------ |
| **index**    | Základní údaje o ročníku                    | [https://spec.utxo.cz/22/](https://spec.utxo.cz/22/)                           |
| **speakers** | Přednášející                                | [https://spec.utxo.cz/22/speakers.json](https://spec.utxo.cz/22/speakers.json) |
| **tracks**   | Programové sekce                            | [https://spec.utxo.cz/22/tracks.json](https://spec.utxo.cz/22/tracks.json)     |
| **events**   | Události                                    | [https://spec.utxo.cz/22/events.json](https://spec.utxo.cz/22/events.json)     |
| **faqs**     | Často kladené dotazy (FAQ)                  | [https://spec.utxo.cz/22/faqs.json](https://spec.utxo.cz/22/faqs.json)         |
| **partners** | Partneři (sponzoři, mediální partneři atp.) | [https://spec.utxo.cz/22/partners.json](https://spec.utxo.cz/22/partners.json) |
| **projects** | Projekty                                    | [https://spec.utxo.cz/22/projects.json](https://spec.utxo.cz/22/projects.json) |
| **bundle**   | Vše v jednom souboru                        | [https://spec.utxo.cz/22/bundle.json](https://spec.utxo.cz/22/bundle.json)     |

Schema si můžete prohlédnout zde:
https://json-schema.app/view/%23%2Fdefinitions%2Fspeaker?url=https%3A%2F%2Fspec.utxo.cz%2Fschema%2F1%2Fbundle.json

## Detaily k jednotlivým ročníkům

### UTXO.22

> 4.-5. června 2022, Gabriel Loci (Praha)

#### Související repozitáře

| Repozitář                                                                     | Popis                  |
| ----------------------------------------------------------------------------- | ---------------------- |
| [utxo-foundation/utxo22-docs](https://github.com/utxo-foundation/utxo22-docs) | GitBook dokumentace    |
| [utxo-foundation/utxo22-web](https://github.com/utxo-foundation/utxo22-web)   | Webová stránka utxo.cz |

## Kontakt

- Web: [utxo.cz](https://utxo.cz)
- Dokumentace: [docs.utxo.cz](https://docs.utxo.cz)
- Foundation: [utxo.foundation](https://utxo.foundation)
