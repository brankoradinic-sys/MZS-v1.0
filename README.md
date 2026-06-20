# MZS v1.0 — Model zaštite susjeda u građevinskim postupcima

> **MZS = PRAVO + STRUKA + RAZUM + TRANSPARENTNOST + DIJALOG**

Operativni okvir za procjenu rizika i definiranje mjera zaštite nekretnina koje se
nalaze u neposrednoj blizini građevinskih zahvata (osobito dubokih iskopa i
podzemnih garaža). Model povezuje tehničku procjenu rizika, geotehničke standarde,
pravni okvir i protokol monitoringa u jedinstven, transparentan postupak koji mogu
koristiti vlasnici nekretnina, investitori, projektanti, vještaci i nadležna tijela.

Model je dio šireg projekta **PZMHS** (Pokret za Mir i Harmoniju Svijesti).

---

## Sadržaj paketa

| Datoteka | Opis |
|---|---|
| `mzs_v1_prezentacija.html` | Vizualna prezentacija modela (arhitektura, moduli, ključne tablice). Otvara se u web pretraživaču. |
| `MZS_v1.0_sazetak_za_institucije.pdf` | Kratki tehnički sažetak modela (2 str.) za prilog dopisima upravnim tijelima. |
| `CC_BY-SA_4.0_licenca_MZS.pdf` | Sažetak licencnih uvjeta i upute za citiranje modela. |
| `README.md` | Ovaj dokument. |

---

## Arhitektura modela — četiri stupa

| Stup | Naziv | Moduli |
|---|---|---|
| 1 | Ulazni i kontekstualni | `0` Ulazni podaci · `B` Geotehnički filter · `C` Eurokod 7 i norme · `I` Vulnerability Index · `P` Pravni okvir |
| 2 | Analitički | `A` TRS (Tehnička klasifikacija rizika) · `J` Trust Index · `F` Ekonomski model |
| 3 | Operativni | `D` Monitoring indeks (MI) · `E` Matrica odgovora · `K` Incident Response Protocol (IRP) · `L` Digitalni dosje susjeda (DDS) · `R` Reverzibilnost odluka |
| 4 | Korektivni / evaluacijski | `G` Human Reasoned Judgment · `H` PZMHS integracija |

**Logika protoka:**
```
ULAZ (0,B,C,I,P) → PROCJENA (A,J,F) → OPERACIJA (D,E,K,L,R) → PROVJERA (G,H)
```

### Ključni instrumenti

- **TRS (Modul A)** — bodovni indeks rizika (0–40 nizak, 41–80 srednji, 81–120
  visok, 121+ kritičan), koji određuje obveznu razinu monitoringa (MI-1 do MI-5).
- **Baseline protokol (Modul D/L)** — referentno stanje = prosjek min. 3 mjerenja
  u 14 dana prije iskopa; svi pragovi su odstupanja od te vrijednosti.
- **IRP (Modul K)** — razine R1–R4 za pukotine, pomake, podzemnu vodu i vibracije
  (PPV), s fail-safe pravilom: najviša aktivirana razina nadjačava sve ostale.
- **Matrica odgovora (Modul E)** — pretvara IRP status u konkretnu akciju, od
  pojačanog monitoringa do hitne obustave radova.

---

## Status — važna napomena o primjeni

MZS v1.0 je **metodološki okvir** za strukturiranje procjene rizika i komunikacije
između stranaka u postupku. Konkretni numerički pragovi (TRS, IRP) trebaju biti
**potvrđeni ili prilagođeni od strane ovlaštenog geotehničkog stručnjaka** za uvjete
konkretne lokacije prije primjene kao formalnog zahtjeva u upravnom postupku. Model
ne zamjenjuje stručno vještačenje, pravni savjet niti odluku nadležnog tijela.

---

## Licenca

Ovaj model i pripadajuća dokumentacija objavljuju se pod licencom

**Creative Commons Imenovanje – Deli pod istim uvjetima 4.0 Međunarodna
(CC BY-SA 4.0)**

- Slobodno korištenje, prilagodba i komercijalna primjena uz navođenje autora.
- Svaka nadograđena verzija (npr. MZS v1.1, v2.0) mora biti objavljena pod istom
  licencom — model ostaje trajno otvoren.
- Puni tekst licence: <https://creativecommons.org/licenses/by-sa/4.0/legalcode>
- Sažetak (deed): <https://creativecommons.org/licenses/by-sa/4.0/deed.hr>

Detalji i praktična objašnjenja: vidi `CC_BY-SA_4.0_licenca_MZS.pdf`.

### Preporučena oznaka autorstva

```
MZS v1.0 — Model zaštite susjeda u građevinskim postupcima
Autor: [ime i prezime / PZMHS]
Licencirano pod CC BY-SA 4.0 — creativecommons.org/licenses/by-sa/4.0/
```

---

## Razvoj

- **Koncept, sinteza i etička/filozofska dimenzija (Modul H):** autor projekta (PZMHS)
- **Tehnička i pravna dorada:** uz pomoć više AI sustava (Claude, GPT, Grok, Qwen)

---

## Verzija

`v1.0` — lipanj 2026.
