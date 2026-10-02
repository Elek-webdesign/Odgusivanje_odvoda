# Odgušenje odvoda - Ivan Marinković

Sajt na jednoj stranici za odgušenje odvoda u Beogradu. Hitne intervencije 0-24h, telefon 061 184 2844.

Svi fajlovi su u jednom folderu, bez podfoldera. Tako ih GitHub prima u jednom potezu.

## Objavljivanje na GitHub Pages

1. Raspakujte `odgusenje-odvoda.zip`.
2. Na GitHub-u otvorite repozitorijum i kliknite **Add file**, pa **Upload files**.
3. Uđite u raspakovani folder, označite **sve fajlove** (Ctrl+A) i prevucite ih u prozor GitHub-a. Treba da ih bude 9, zajedno sa ovim README fajlom i fajlom `.nojekyll`.
4. Kliknite **Commit changes**.
5. Otvorite Settings, pa Pages. Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)**, pa Save.
6. Posle minut-dva sajt radi na `https://<korisnik>.github.io/<repozitorijum>/`.

Fajl `.nojekyll` je skriven u Windows-u. Ako ga ne vidite, uključite View, pa Hidden items. Sajt radi i bez njega.

## Forma za upite

Pre objave forma ne šalje upite nigde. Posetilac vidi poruku "Upit je poslat", ali upit ne stiže.

Da bi upiti stizali na mejl:

1. Napravite besplatnu formu na [Formspree](https://formspree.io) i kopirajte njen link (izgleda kao `https://formspree.io/f/abcdwxyz`).
2. U `index.html` nađite red `var FORM_ENDPOINT = '';` i upišite link između navodnika.
3. Ponovo otpremite `index.html` na GitHub.

## Fajlovi

| Fajl | Šta je |
| --- | --- |
| `index.html` | ceo sajt: tekst, stil i skripta |
| `sahta.webp` | pozadina na početku stranice |
| `kuhinja.webp` | slika u delu o hitnim intervencijama |
| `logo.webp` | logo u zaglavlju |
| `favicon-32.png`, `favicon-64.png` | ikonica u tabu browsera |
| `favicon-180.png` | ikonica kad se sajt doda na početni ekran telefona |
