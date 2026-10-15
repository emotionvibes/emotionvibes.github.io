# EmotionVibes — private review stage

Astro static site, RU default + editable LT translations. Work is confined to `emotionvibes-preview`. No deployment workflows are included. Do not merge or enable GitHub Pages without separate owner approval.

## Local use

Node 22.12+ or Node 24. `npm ci`, then `npm run dev`. `npm run build` creates the static site in `dist/`. The root page is Russian; localized pages are under `/ru/` and `/lt/`.

`EmotionVibes-preview.html` is an offline review copy: download and open in a browser. Its hash navigation simulates the same pages. It contains only neutral demo content. It is not a hosted private website; the GitHub source itself is public.

## Turinys be programavimo

1. Atidarykite https://app.pagescms.org ir prisijunkite su `emotionvibes` GitHub paskyra.
2. Jei prašoma, suteikite Pages CMS prieigą TIK `emotionvibes/emotionvibes.github.io` saugyklai.
3. Pasirinkite `emotionvibes-preview` šaką. `main` nekeiskite.
4. Pasirinkite „Klausimai ir atsakymai“, „Mano mintys“, „Meditacijos“ arba „Muzika ir grojaraščiai“.
5. Pridėkite įrašą, užpildykite RU ir LT laukus ir išsaugokite. Unikalus adresas turi būti iš mažųjų lotyniškų raidžių, skaičių ir brūkšnelių, pvz. `pirma-praktika`; jo nekeiskite po publikavimo.
6. Klausimų temos numeris atitinka „Klausimų temos“ sąrašo vietą, skaičiuojant nuo 0. RU ir LT temos turi būti ta pačia tvarka.
7. Muzikai įveskite 11 simbolių YouTube vaizdo ID iš `watch?v=...` nuorodos. Grojaraščiui galima pridėti HTTPS nuorodą. Naujausi įrašai rikiuojami pagal datą.
8. Nuotraukas ir originalius logotipus įkelkite vaizdų laukuose. Kontaktų laukus užpildykite tik patvirtintomis HTTPS nuorodomis.

Redaktoriaus konfigūracija paruošta, bet GitHub App prijungimas ir realus išsaugojimas redaktoriuje dar netikrinti: tam reikia savininkės prisijungimo. Redaktorius keičia GitHub failus; šiame etape pakeitimai svetainės nepaskelbia. Offline peržiūra yra momentinė kopija ir po redagavimo turi būti sugeneruota iš naujo.

## Privatumas ir klausimų gavimas

Viešoje saugykloje visi failai ir jų istorija, įskaitant juodraščius, yra vieši. Čia nesaugokite lankytojų žinučių, vardų, el. pašto ar privačių tekstų. Klausimai ir straipsnis yra pažymėti kaip demonstraciniai, ne kaip autorės patvirtintas turinys.

Pradiniam klausimų gavimui numatyta asmeninio Telegram pokalbio nuoroda. Ji bus aktyvi tik patvirtinus kontaktą. Lankytojui reikės Telegram; žinutė nebus automatiškai publikuojama. Šlamštą galima blokuoti ir pranešti Telegram, tačiau CAPTCHA ir svetainės dažnio ribojimo šis kelias neturi. Neskelbkite asmens tapatybės ar žinutės be atskiro jo sutikimo. Telegram pokalbis nėra svetainėje laikomas klausimas.

Integruotai formai reikėtų atskiro privataus priėmimo backend su CAPTCHA, serverio dažnio ribojimu, nemokamo plano kvotomis ir duomenų saugojimo taisyklėmis. Tokia paslauga šiame etape neprijungta. Naršyklėje ar GitHub niekada nelaikykite botų raktų ar kitų paslapčių.

YouTube nesiunčiamos užklausos iki paspaudimo įkelti grotuvą; nėra išorinių miniatiūrų, analitikos ar automatinio paleidimo. Šriftams kol kas naudojami vietiniai sisteminiai pakaitalai, todėl nėra užklausų į Google Fonts.

## Before any public launch

Owner approval is required. Replace/approve demo content, confirm contacts, original images and privacy text; verify CMS editor using the owner account. Remove preview `noindex` and robots exclusion, add canonical links and sitemap, and only then separately enable a deployment. `noindex` is not access control.

## Klausimų filtrai ir turinio redagavimas

Redaguojant klausimą Pages CMS, laukelyje **Temos (galima pasirinkti kelias)** pasirenkamos žymos iš sąrašo: Protas / Ум, Širdis / Сердце, Miegas / Сон, Meditacija / Медитация, Santykiai / Отношения, Emocijos / Эмоции. Angliškų kodų ranka rašyti nereikia. Tą patį klausimą galima priskirti kelioms temoms. Svetainėje vieno paspaudimo filtrai veikia kartu su teksto paieška ir kategorijomis, o „Išvalyti filtrus“ viską atstato.

Naujus klausimus redaktoriuje įrašykite tik anonimizuotus ir autorės patvirtintus; viskas GitHub viešoje saugykloje, net juodraščiai, yra matoma kitiems. Dabartiniai klausimai yra demonstraciniai. Pages CMS prisijungimas ir tikras išsaugojimas dar nepatikrinti, tam reikės savininkės veiksmų.
