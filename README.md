# CRMETDR — superseded by CLBDR

> **⚠️ This repository has been absorbed into the [Common Liturgical Books Data Repository (CLBDR)](https://github.com/CatholicOS/clbdr) and is archived.**

The Common Roman Missal Editio Typica Data Repository (CRMETDR) proposed canonical identifiers for the editions of the Latin Roman Missal. That work now lives in the CLBDR, a single registry for **all** the liturgical books of the Roman Rite and their editions — which dissolves the acronym collisions that per-book registries would multiply (a Martyrology editions repository would also have been "CRMETDR").

Everything from this repository was carried over:

- the **Missal edition line** (1474–2008), with natures and reigning popes → [`clbdr/data/editions.json`](https://github.com/CatholicOS/clbdr/blob/main/data/editions.json), IDs unchanged (`missale_romanum_1970`, …) and short forms (`mr1970`, …) preserved as attributes;
- the **historical notes** on the Roman Missal → [`clbdr/docs/missale-romanum.md`](https://github.com/CatholicOS/clbdr/blob/main/docs/missale-romanum.md);
- the **vernacular identification proposal** (BCP47 tags: `missale_romanum_2011_en_US`) → generalized for all books in [`clbdr/docs/schema.md`](https://github.com/CatholicOS/clbdr/blob/main/docs/schema.md), open questions included.

Consumers referencing the edition keys (such as the [CLEDR](https://github.com/CatholicOS/cledr)) need no changes: the keys are identical in the CLBDR.
