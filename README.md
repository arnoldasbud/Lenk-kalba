# Lenkų kalba

Lenkų kalbos programėlė pradedantiesiems lietuviams, nuo nulio iki A1 lygio (CEFR).

**Antras kursas – egiptiečių arabų kalba kelionėms.** Perjungiama mygtuku „Šiandien“ skiltyje arba Nustatymuose → Kursas. Kiekvieno kurso pažanga saugoma atskirai (`lenku-kalba-v1` ir `arabu-kalba-v1`). Arabų kurse: 16 pamokų, 4 etapai (pasisveikinimai ir skaičiai; kainos, derybos, kioskas, laikas; kavinė, restoranas, maistas; taksi, kelias, viešbutis, vaistinė), ~250 žodžių ir frazių arabiškai su lotyniška transliteracija, dialogai, 10 gramatikos temų ir neprivalomas raidynas (4 temos su skaitymo pratybomis). Rašoma transliteracija (atlaidžiai: be apostrofų, dvigubų raidžių), balsas ir balso atpažinimas ar-EG. Pamokose pastabos apie Tuniso tarmę ir prancūzų kalbą.

**Kursas:** 24 pamokos, 6 etapai po 4 pamokas (~2 savaitės etapui), ~370 žodžių. Kiekvienoje pamokoje gyvas dialogas, žodžiai, trumpa pastaba ir gramatikos užduotys.

**Gramatika:** atskiras skyrius (Pamokos → Gramatika), 14 temų su paaiškinimais lietuviškai ir pratybomis: būti, asmenuotė, klausimai, skaičiai, galininkas, kilmininkas, vietininkas, įnagininkas, giminės ir būdvardžiai, noriu/galiu/privalau, laikas, kryptis, būtasis ir būsimasis laikas. Tema atsiveria kartu su pamoka, kurioje ji pirmą kartą reikalinga.

**Pratybos:** pasirinkti vertimą, atpažinti iš klausos, suprasti sakinį iš klausos, gramatikos formos, parašyti lenkiškai, sudėlioti sakinį, įrašyti praleistą žodį, diktantas. Vaidmenų žaidimas: atsakai už vieną dialogo pašnekovą raštu arba balsu (balso atpažinimas pl-PL, kur naršyklė palaiko).

**Kartojimas:** žodžiai, dialogų sakiniai ir gramatikos užduotys (kasdienė užduotis „Gramatika“) kartojami su intervalais (1, 2, 4, 8, 16… dienų). Sakinių kortelės: naujos – diktantas, pažįstamos – parašyk ar pasakyk lenkiškai.

**Progresija ir tikslai:**
- nauja pamoka atsiranda ne dažniau kaip kas 2 dienas ir tik pakartojus šiandienos korteles;
- į kitą etapą – kai kiekvienos pamokos 80% žodžių „moku“, pratybos ≥80% dviem dienomis, etapo gramatikos temos ≥80%, etapo testas ≥80% (jame ir ankstesnių etapų žodžiai) ir pažymėti kalbėjimo tikslai.

## Kuo remiasi

- **Aktyvus prisiminimas ir išdėstytas kartojimas** – du veiksmingiausi mokymosi būdai: Dunlosky ir kt. (2013), [Improving Students' Learning With Effective Learning Techniques](https://www.psychologicalscience.org/journals/pspi/1529100612453266/).
- **Keturios kryptys** (P. Nation): suprantamas klausymas, kalbėjimas, kalbos sandara ir sklandumas – [The Four Strands](https://www.wgtn.ac.nz/lals/resources/paul-nations-publications/paul-nations-publications/publications/foreign-language_1125.pdf).
- **CEFR A1** „galiu“ teiginiai etapų tikslams – [Europos Taryba, Global scale](https://www.coe.int/en/web/common-european-framework-reference-languages/table-1-cefr-3.3-common-reference-levels-global-scale).
- Kaitaliojimas (mišrios užduotys iš skirtingų pamokų) ir frazių mokymasis (dialogų sakinių kortelės).

Garsas: telefono kalbos sintezė (lenkiškas balsas pl-PL, arabiškas ar-EG arba bet kuris arabiškas).

Atidaryti: https://arnoldasbud.github.io/Lenk-kalba/

Viskas viename `index.html` faile, be priklausomybių (arabų kurso turinys – atskirame `<script>` bloke `AR_COURSE`). Pažanga saugoma naršyklėje (localStorage). Veikia be interneto (`sw.js`). Versija keičiama `index.html` (`VERSION`) ir `version.json`.
