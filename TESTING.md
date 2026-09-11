# PikadoBro — testiranje

Hvala na testiranju! 🎯

Probaj aplikaciju kao pravi trening, ne samo klikanjem kroz ekrane. Posebno javi ako:

- neko pravilo ili bodovanje nije ispravno
- Undo napravi nešto neočekivano
- timer u Speed Gameu zapne ili preskoči metu
- Checkout Trainer / Challenge ponudi ili zabilježi nešto pogrešno
- aplikacija izgubi rezultat nakon refresh/restarta
- Backup / Restore ne vrati statistiku
- nešto izgleda loše ili je teško pritisnuti na mobitelu/tabletu

Kod prijave buga napiši: **igra + što si napravio + što se dogodilo + što si očekivao**. Screenshot je bonus.

Podaci su lokalni u browseru/uređaju. Brisanje podataka browsera briše i PikadoBro podatke ako prije toga nije napravljen JSON backup.

## FixTheThing
- Try Custom target 20 and enter `T1, 20, 5`: result should be 1/3 hits.
- Target 20: S20, D20 and T20 must all count as hits.
- Target D20/T20: only the exact ring counts.
- Finish all 10 rounds and verify FixTheThing appears in Statistics.
- Automatic should stay locked until enough relevant training data exists; existing RTW/Bob's 27 data may contribute.


## FixTheThing v0.17
- Meta 20 mora ponuditi S20/D20/T20 te kratice za susjede 5 i 1.
- Tijekom igre ne smije prikazivati live hit score ni postotak.
- Provjeri da kratice upisuju točno jednu strelicu i da puna tipkovnica i dalje radi.
