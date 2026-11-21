# LESCC Living Archive & Anthropology Layer

The LESCC bid proposes a community-run living archive that records how the neighborhood's cultures actually live, and uses that record to shape programming, support the Parks fee, and protect the people it records.

Data file: `lescc-anthropology-layer.json` (this folder). Everything here is proposed; nothing is in operation yet.

## Core concept

The archive serves two audiences at once.

- For residents: a record of the neighborhood's living culture
- For NYC Parks: an ongoing evidence base for bid scoring and operational compliance
- Pitch line: "LESCC doesn't just host culture, it keeps a running record of how the neighborhood's cultures actually live."

## Archive operations

Paid community ethnographers from each group record the neighborhood in its own languages.

| Group | Languages | Notes |
|---|---|---|
| Chinese elders and families | Cantonese, Mandarin | |
| Loisaida community | Spanish, English | Puerto Rican and Dominican heritage |
| Jewish heritage | English | |
| Artist community | English | |
| Youth practitioners | English, Spanish | With Girls Club and LES Yearbook |

- Records: oral histories, a shared cultural calendar, a map of living cultural places (churches, mahjong parlors, botánicas, bakeries, galleries, social clubs), and foodways
- Access in Cantonese, Mandarin, Spanish and English
- Archive findings set storefront rotations, the booking desk and the public space layout

## Fit with the Parks scoring criteria

The file maps the archive to five RFP criteria.

| Criterion | Archive answer |
|---|---|
| Operator experience | Track record of partner organizations: Loisaida Inc., Tenement Museum, University Settlement, Lower East Side Girls Club |
| Pricing and public benefit | Free and low-cost access set against local poverty (21%) and limited English proficiency (24%) |
| Capital investment | Restoration of the Allen Street building plus a permanent public archive |
| Design and public space | Layout co-designed with community groups from documented cultural practice |
| Sustainability and performance | Annual measurement and program renewal |

## Governance

A Cultural Council with a seat for each community group governs the archive.

- Communities own their records
- Strict consent protocol
- No data extraction for commercial marketing

## Tensions and how the bid answers them

Two risks are named in the file, each with a proposed answer.

- **Food culture:** saying "food vendors are unnecessary" alienates local food culture. The bid reframes it as "generic commercial concessions are unnecessary" and brings local food makers (Congee Village, Chinese bakeries, Empanada Mama, Porto Rico Coffee) in as cultural partners and suppliers.
- **Displacement:** culture-led uplift can raise rents and push out the elders, artists and legacy merchants the hub celebrates. Answers: a Cultural Continuity Fund taking a fixed share of coalition pledges for legacy businesses, and annual reporting of displacement measures (legacy closures, vacancy, rent spikes) alongside uplift.

## Sources

The `source_citation` fields in the JSON name internal LESCC documents and frameworks, not outside data.

- The 321 vendors figure is checked in `../README.md`, section 6 (NYC restaurant inspection records)
- Poverty (21%) and limited English proficiency (24%), checked 2026-11-21 against ACS 2020-2024 5-year (via Census Reporter), using the same tracts as `../README.md` section 6
- Poverty (B17001): 17.5% in tracts reaching within 400 m of Allen & Broome, 25.0% within 600 m; 21% sits inside that range
- Limited English (C16002): 20.0% of households are limited-English within 400 m, 23.9% within 600 m, so 24% matches the wider area
- Individuals (B06007): 26.3% (400 m) and 29.2% (600 m) of people aged 5+ speak English less than "very well", so the household measure is the conservative one

<!-- llm: claude-opus-5-5 | 2026-11-21 | lescc-hackathon/data/raw/lescc-anthropology-layer.md | created: README for the LESCC anthropology layer JSON -->
