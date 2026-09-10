# PikadoBro — kratke upute za igre

## X01

Odaberi **301, 501, 701, 901 ili 1001** te Double Out ili Master Out. Nakon svake runde upiši ukupan rezultat tri strelice. Bust vraća score na stanje prije te runde.

Kad remaining padne na **60 ili manje**, PikadoBro automatski prati checkout fazu. Od **61 do 170** možeš označiti **POKUŠAJ IZLAZA** ako taj visit stvarno igraš kao checkout. Kod završenog lega aplikacija pita kojom si strelicom izašao.

Maksimalan broj rundi je: 301 = 10, 501 = 15, 701 = 18, 901 = 21, 1001 = 24.

## High Score

Odaberi **7, 8 ili 15 rundi**. U svakoj rundi upiši zbroj tri strelice. Cilj je napraviti što veći ukupni score.

## Split Score

Počinješ sa **40 bodova**. Mete su:

`15 → 16 → Double → 17 → 18 → Triple → 19 → 20 → Bull`

Kod brojčanih meta unosi se broj pogodaka/vrijednost pogodaka u ciljanu metu, a kod Double/Triple runde osvojeni bodovi. Ako sa sve tri strelice potpuno promašiš zadanu metu, trenutni score se prepolovi. Kod neparnog broja zaokružuje se u korist igrača, npr. **75 → 38**.

**Split Score Back** koristi ista pravila obrnutim redoslijedom.

## Round the World

Odaberi **Singles, Doubles ili Triples** i prolazi mete od 1 do 20. Imaš najviše **40 rundi**.

Upisuješ koliko je od tri strelice pogodilo točan traženi prsten. Ako upišeš **0**, ostaješ na istoj meti. Ako pogodiš 1, 2 ili 3 puta, prelaziš na sljedeći broj.

Opcionalni završni Bull ovisi o modu: Singles traži **Bull 25**, Doubles traži **DB 50**, a Triples prihvaća **Bull 25 ili DB 50**.

## Checkout Trainer

Checkout Trainer je vježba izlaza; promašaj ne prekida trening. Trening možeš ograničiti brojem rundi ili vremenom.

- **PDC** — vrti standardne mete: 40, 32, 36, 50, 20, 8, 4, 16 i 24.
- **Random** — nasumične mete 2–40.
- **Manual** — sam upisuješ mete koje želiš vrtjeti kroz trening.
- **Crazy** — vrti parne checkout mete i automatski ih mijenja nakon nasumičnih 5–15 sekundi uz zvučni signal.

Za svaku rundu označi **IZLAZ** ili **PROMAŠAJ**. PikadoBro broji runde, pogotke, promašaje i checkout postotak.

## Checkout Challenge 2–170

Krećeš od **2** i moraš završiti svaki mogući checkout prije nego prijeđeš na sljedeći. Bogey brojevi koji se ne mogu završiti u tri strelice automatski se preskaču.

Za uspješan izlaz označi je li napravljen s **1, 2 ili 3 strelice**. Ako ne izađeš, odaberi **PROMAŠAJ** i ostaješ na istoj meti. Napredak se sprema pa Challenge možeš nastaviti drugi dan. Nakon 170 počinje novi run od 2, a prethodna povijest ostaje spremljena.

## Bob's 27

Počinješ s **27 bodova** i redom gađaš D1, D2 ... D20 pa Bull. Na svakoj meti imaš tri strelice.

Ako pogodiš double, dodaje se njegova vrijednost za svaki pogodak. Ako sva tri puta promašiš, vrijednost tog doublea se oduzima. Ako score padne na **0 ili manje**, igra završava.

## Undo i izbornik

**Undo vraća samo posljednji uneseni visit i može se koristiti samo jednom.** Nakon Undo-a nije moguće nastaviti vraćati starije rezultate; novi Undo postaje dostupan tek nakon novog unosa.

Tijekom igre dvostruki klik ili double-tap na prazni dio ekrana otvara skriveni izbornik.


## Checkout Challenge — 2 Dart / 3 Dart Finishes

Checkout Challenge je progresivni trening izlaza s prikazanim rutama.

- **2 Dart Finishes:** prolazi kroz sve scoreove od 2 do 100 koji se mogu zatvoriti u najviše dvije strelice. Neparni izlazi su uključeni; scoreovi koji nisu mogući u dvije strelice automatski se preskaču.
- **3 Dart Finishes:** prolazi kroz validne checkoutove 99–170 koji se mogu zatvoriti u najviše tri strelice. Bogey brojevi se preskaču.
- Ispod mete PikadoBro prikazuje preporučenu rutu i do dvije alternative.
- **PROMAŠAJ** ostavlja igrača na istoj meti. Uspješan izlaz označava se brojem iskorištenih strelica.
- Napredak se automatski sprema. **Novi ciklus** kreće od početka, ali čuva stare cikluse radi usporedbe napretka. Povijest se može zasebno obrisati.


### Checkout Challenge v0.12
Prikazuje preporučenu checkout rutu. U treningu se bilježi samo **IZLAZ** ili **PROMAŠAJ**; broj strelica se ne traži. Promašaj ostavlja igrača na istoj meti. Standardne rute imaju prednost pred matematički mogućim, ali nepraktičnim kombinacijama.
