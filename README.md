# IFI6229.DT Rakenduste programmeerimise kursus

#### Selleks, et läbida projekti osa ainest:

1. On vaja esitada enda projekti meile aktsepteerimiseks **08.11** päeva lõpuni kuni **23.59**. Pärast positiivse vastuse saamist loome repositooriumi rakenduste-programmeerimine-2021 alla teil on vaja eraldi #projekt kanalil  teada anda kellega projekti teed, mis projekti nimi on, mis on eesmärk teistele tutvustamiseks.
2. Tuleb luua korralik **README**, mis selgitab kõike projektiga seonduvat (autorid, kuidas kasutada, wireframe lingid jne).
3. On vaja luua low-fidelity wireframe projekti jaoks [näide](https://images.ctfassets.net/qop92tnevinq/0LwOZ4G6nxFy7zp62aRqg/a3e19a8955b3a2ef97f3ddf3a25d0b45/low-fidelity-wireframes-web.png?fm=webp&q=80). Võite teha käsitsi ka, siis tuleb lihtsalt pildid teha ja pärast enda repositooriumis panna `/wireframes` kausta.
4. Kui backendina kasutada Javat, siis tuleb implementeerida ka Everypay makselahendus nii backendis kui frontendis (backendi Java näide on saadaval Githubis enne projekti alustamist).
5. Seejärel saate hakata kirja panema soovitud funktsionaalsuseid ning saate vaikselt vastavalt nendele hakata looma issuesid.
6. Pärast issuede paika panemist planeerite 4 sprinti (algab esmaspäevaga ja lõpeb järgmise esmaspäevaga, **15.11-22.11**, **22.11-29.11**, **29.11-06.12**, **06.12-13.12**). Ehk luua vastavad *milestone*-d sprintidele. Seejärel on aega kuni **17.12.2021** ja põhieksamil on enda projekti esitamine. Järeleksam **21.01.2022**.
7. Iga sprindi jooksul peab tegema enda projekti discordi kanalis vähemalt 2 standupi kirja panekut (mida eelmine kord tegid, mida hakkad täna tegema ja mis takistused on). **See tähendab, et iga nädal on vaja teha vähemalt 2 standupi.**
8. Teha vähemalt **5 code review**-i kellegi teise projektile. Kui 5 reviewd on täis, siis saata kõikide reviewde lingid korraga mõlemale: mihvah@tlu.ee / raimo.pregel@tlu.ee
9. Testidega on tarvis **80%** projektist katta ehk kui nt Reactis loote komponendid, siis 80% komponentidest on vaja katta testidega. Võivad olla lihtsad testid, aga peavad eksisteerima. 
10. Peab osalema vahekokkuvõtetes ja esitada 2 korda enda projekti tunnis teiste ees (**22.11** ja **03.12**).


## Workflow

Alati tuleb koodi commitida main branchi läbi pull requestide ehk otse main branchi me ei commiti. 

1. Loote main branchi põhjal uue branchi
2. Teete oma muudatused ainult sinna brachi, peamine töö toimub seal
3. Kui viimased muudatused valmis, luua ```Pull request``` (kui see lahendab mingeid ticketeid, kirjutada ka ```closes #number```)
4. Teie projektikaaslane peab vastu võtma teie PR-i (ise vastu ei võta) ja soovitavalt ```Rebase and merge```. [Rohkem infot siit](https://rietta.com/blog/github-merge-types/)
5. Võimalikud konfliktid on vaja ka lahendada, et mis kood jääb peale. 

‼️ Code review teistelt võib teha ka pärast PR vastu võtmist ja muudatusi saab ka siis hiljem järgi teha. Ehk enda projekti väliselt review saamisel ei pea ootama jääma.

‼️ Andke teada enda projektinimelises kanalis Discordis, kui basic setup tehtud, siis saab ```branch protectioni``` peale panna, et kõik see ära ei ununeks 🙂

### Tähtsad kuupäevad

**19.11.21** — Aktiivne arendus tunni ajal, saame olla ka ise abiks video vahendusel **(vabatahtlik)**.

**22.11.21** — Vahekokkuvõte, kõikide projektide senise tehtud töö esitamine **(kohustuslik)** ja pärast seda aktiivne arendus **(vabatahtlik)**.

**03.12.21** — Vahekokkuvõte, kõikide projektide senise tehtud töö esitamine **(kohustuslik)** ja pärast seda aktiivne arendus **(vabatahtlik)**.

**06.12.21** — Viimased tagasiside küsimise võimalused enne **17.12.2021** eksamit **(vabatahtlik)**.


### Konsultatsioonid

Probleemide ilmnemisel võib kirjutada #general-problems kanalisse ja kõik on teretulnud abistama üksteist, et saada aine korralikult tehtud 🙂 Saame samuti aidata, kui võimalus tekib.

### Juurutamine (deployment)

Võimalik, et deploymenti teeme eraldi ja mitte dockeriga, kuna enamikel inimestel on dockeriga eriti aeglane teha projekti. Veel tutvustame täpsemalt pärast 2. sprinti - võimalused on Digital Oceans, Netlify, Heroku jms.

### Google Meets:

- Mihkli (esmaspäeviti): https://meet.google.com/brf-ecmf-ctf

- Raimo (reedeti): https://meet.google.com/pai-ziwn-dmq

### Muu info: 


Ainekaart: https://shorturl.at/akK07

Kursuse WIKI: https://github.com/rakenduste-programmeerimine-2021/kursus/wiki

Discord: https://discord.gg/V7UG6tqs

Loengute salvestused: https://drive.google.com/drive/folders/1jDNBE4VNYK9d1D10hATTZZH93ryxC7ME?usp=sharing

Koduste tööde jaoks repo link e-mailile: mihvah@tlu.ee / raimo.pregel@tlu.ee

Kodused tööd: https://github.com/rakenduste-programmeerimine-2021/kursus/wiki/Kodut%C3%B6%C3%B6d

Koduste tööde kontroll: https://docs.google.com/spreadsheets/d/171kF34T1gnhsIz12kXfEQPTIg_POtsU2FIPfUFGVYpY/edit?usp=sharing
