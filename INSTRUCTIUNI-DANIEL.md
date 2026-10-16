# Sistem Antrenament — DANIEL (16 octombrie 2026, v1.1 dupa bioimpedanta)

Aceeasi aplicatie, acelasi format (cum / lucreaza / atentie / daca e prea greu),
doar programul e schimbat. Pentru Daniel: 39 de ani, 70 kg, incepator care revine,
obiectiv masa musculara. Bioimpedanta din 16.10: 71 kg, 29,3 % grasime, 50,2 kg
masa slaba, grasime concentrata pe trunchi -> strategie de RECOMPOZITIE, nu bulk.

## Fisiere
1. **app.compiled.js** — aplicatia cu programul lui Daniel
2. **index.html** — acelasi ca la versiunea ta, nu se schimba
3. **INSTRUCTIUNI-DANIEL.md** — acest fisier

## Deploy
Repo SEPARAT de al tau (alt deploy, alt link), ca sa nu se amestece datele.
1. Copiezi `index.html` din repo-ul tau in repo-ul nou.
2. Pui `app.compiled.js` (fisierul primit, redenumit cu PUNCT) langa el.
3. Commit, astepti 2-3 minute, deschizi pe telefonul lui Daniel.
4. Baza de date locala are alt nume (`AntrenamentDaniel_DB`), deci chiar daca
   deschide ambele linkuri pe acelasi telefon, nu se suprascriu.
5. La prima deschidere NU apare notificarea de nivel recalculat — porneste curat
   de la nivelul 1.

## Programul

| Zi | Antrenament | Exercitii | Serii |
|---|---|---|---|
| Luni | SUPERIOR A — accent impingere + mers pe banda | 7 + 1 | 23 |
| Marti | INFERIOR A — accent genuflexiune | 6 | 20 |
| Miercuri | PAUZA | — | — |
| Joi | SUPERIOR B — accent tragere + mers pe banda | 7 + 1 | 23 |
| Vineri | INFERIOR B — accent indreptari / fesieri | 7 | 22 |
| Sambata, Duminica | PAUZA | — | — |

Fiecare grupa mare e lucrata de 2 ori pe saptamana, 12-16 serii pe grupa.
Durata estimata: 60-75 de minute, cu pauzele respectate (2,5-3 min la compuse,
60-90 s la izolare).

**Luni:** Presa cu gantere pe banca dreapta 4×6-10 · Ramat cu bara 4×6-10 ·
Presa de umeri cu gantere 3×8-12 · Helcometru priza larga 3×10-12 ·
Ridicari laterale 3×12-15 · Extensii triceps la cablu 3×12-15 · Flexii ciocan 3×10-12 ·
Mers pe banda 15-20 min (optional, nepenalizat)

**Marti:** Genuflexiuni cu bara 4×6-8 · Indreptari romanesti 3×8-10 ·
Presa de picioare 3×10-12 · Flexii femurali culcat 3×12-15 ·
Ridicari pe varfuri in picioare 4×12-15 · Plank 3×45-60 s

**Joi:** Tractiuni la bara (asistate daca e nevoie) 4×6-10 · Presa inclinata cu
gantere 4×8-10 · Ramat cu gantera pe banca 3×10-12/parte · Fluturari la cablu
3×12-15 · Face pull 3×15 · Flexii cu bara EZ 3×10-12 · Extensii triceps deasupra
capului 3×12-15 · Mers pe banda 15-20 min (optional, nepenalizat)

**Vineri:** Indreptari cu trap bar 4×5-8 · Fandari cu gantere in mers 3×10/picior ·
Hip thrust cu bara 3×10-12 · Extensii de genunchi 3×12-15 · Flexii femurali sezand
3×12-15 · Ridicari pe varfuri sezand 3×15 · Ridicari de genunchi atarnat 3×10-15

## Ce e diferit fata de programul tau
- Greutati libere ca baza (bara, gantere), aparate doar pentru izolare.
- Repetari 6-10 la compuse, 12-15 la izolare. Seturile merg pana la 1-2 repetari
  de epuizare, nu 2-3.
- Progresia e pe KILOGRAME (progresie dubla): cand face maximul de repetari la
  toate seturile, urca greutatea. Butonul `+` din aplicatie urca cu pasul potrivit
  fiecarui exercitiu: 1 kg la umeri si biceps, 2-2,5 kg la piept si brate,
  5 kg la genuflexiuni, indreptari si gambe, 10 kg la presa si hip thrust.
- Mers pe banda 15-20 min doar luni si joi (zilele de superior), optional si
  nepenalizat, pentru grasimea de pe trunchi. In zilele de picioare, nu.
- Nutritie = RECOMPOZITIE: calorii la mentinere (2000-2200 kcal), fara surplus,
  proteina 140-150 g pe zi, somn 7-8 ore. Scris in regulile din aplicatie.
- Primele 2 saptamani sunt scrise explicit ca perioada de reinvatare a miscarilor,
  cu greutati mici. Progresia reala incepe din saptamana 3.

## Penalizari
Neschimbate: 10 XP pe exercitiu sarit intr-o zi de antrenament. Abdomenul
(exercitiile marcate ca finisher) nu se penalizeaza. Miercuri, sambata si duminica
nu se penalizeaza. Modul plecare ramane fara penalizari.

## Modul plecare (acasa)
Refacut pe aceeasi impartire Superior / Inferior, 4 zile, cu greutatea corpului,
banda elastica, rucsac cu carti si o masa solida. Fara mers afara obligatoriu.

## De verificat dupa deploy
- Jos sunt trei butoane: SALA, PROGRES, SETARI.
- Luni scrie SUPERIOR, primul exercitiu "Presa cu gantere pe banca dreapta".
- Miercuri apare ca PAUZA DE MIJLOC, fara exercitii.
- Vineri primul exercitiu e "Indreptari cu trap bar".
- Butonul de incalzire arata textul pentru "zi de partea superioara" / "zi de picioare".
- Nu apare nicio notificare de nivel recalculat la prima deschidere.

## Cum se masoara progresul
Cantarul NU e indicatorul. La recompozitie greutatea sta pe loc sau scade lent.
Se urmaresc, o data la 4 saptamani, pe acelasi cantar, dimineata, pe nemancate:
procentul de grasime (tinta: sub 25 % in 3 luni, sub 20 % in 6), masa musculara
(sa creasca sau macar sa nu scada) si greutatile de pe bara (sa creasca saptamanal).
Plus poze din fata / profil / spate in aceleasi conditii.

## De ajustat dupa poze
Daca are umeri ingusti sau spate slab, mutam serii dinspre piept spre umeri si spate.
Programul de baza ramane acelasi.
