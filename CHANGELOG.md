# CHANGELOG — MZS v1.0

Sve značajne izmjene ovog projekta bit će dokumentirane u ovoj datoteci.

Format prati [Keep a Changelog](https://keepachangelog.com/hr/1.0.0/).

---

## [1.0.0] — lipanj 2026.

### Dodano
- Modul 0 — Ulazni podaci (Input Layer)
- Modul A — Tehnička klasifikacija rizika (TRS), bodovni sustav
- Modul B — Geotehnički filter (sufozija, podzemna voda, tip tla)
- Modul C — Eurokod 7 i norme (EN 1997-1/2, EN 1536, ISO 18674)
- Modul D — Monitoring indeks (MI-0 do MI-5) s vezom TRS → MI
- Modul E — Matrica odgovora (IRP status → konkretna akcija)
- Modul F — Ekonomski model (trošak suradnje vs. trošak sukoba)
- Modul G — Human Reasoned Judgment (HRJ)
- Modul H — PZMHS integracija (etička i filozofska dimenzija)
- Modul I — Vulnerability Index (VI), skala 0–100
- Modul J — Trust Index (TI) za procjenu pouzdanosti investitora
- Modul K — Incident Response Protocol (IRP), razine R1–R4
- Modul L — Digitalni dosje susjeda (DDS) + Baseline protokol
- Modul P — Pravni okvir (ZPU, ZOG, ZUP, ZOO, Zakon o vodama)
- Modul R — Reverzibilnost odluka (IR-5 logika, PNR točke)
- Logička struktura: 4 stupa (ulazni, analitički, operativni, korektivni)
- Formula: MIR = PRAVO + STRUKA + RAZUM + TRANSPARENTNOST + DIJALOG
- Baseline protokol: min. 3 mjerenja u 14 dana prije iskopa
- Fail-safe pravilo: R4 na bilo kojem parametru nadjačava sve ostale
- Kontekstualni faktor (IC): IC-1 kritična infrastruktura / IC-2 urbano /
  IC-3 ruralno (pragovi ±20%)
- Vizualna prezentacija (HTML, blueprint stil)
- Sažetak za institucije (PDF, 2 str.)
- Licencna dokumentacija CC BY-SA 4.0 (PDF)
- README.md, CONTRIBUTING.md, CHANGELOG.md

### Razvoj
- Koncept, sinteza i etička/filozofska dimenzija: autor projekta (PZMHS)
- Tehnička i pravna dorada: AI suradnici (Claude, GPT, Grok, Qwen, Poe)
- Pilot slučaj: k.č. 3977/1 vs. k.č. 3976/3 k.o. Blato, Zagreb (2025–2026)

### Napomena
Numerički pragovi (TRS, IRP) u v1.0 su inicijalne vrijednosti temeljene
na europskim normama i stručnoj procjeni. Preporučuje se potvrda od strane
ovlaštenog geotehničkog stručnjaka za svaku konkretnu primjenu.

---

## [Planirano — buduće verzije]

### v1.1 (planirano)
- Validacija TRS/IRP pragova od strane ovlaštenih geotehničara
- Dopuna case studyjevima iz prakse
- Proširenje Modula P za jurisdikcije izvan RH

### v2.0 (vizija)
- Interaktivni digitalni kalkulator (web aplikacija)
- Integracija s IR-5 modelom za složenije slučajeve
- Višejezična verzija (EN, DE)
- Proširenje na ruralni kontekst i infrastrukturne zahvate

---

*Format: [Verzija] — datum objave*
*Licenca: CC BY-SA 4.0*
