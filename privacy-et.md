---
layout: default
title: Privaatsuspoliitika — Koosolek
---

# Privaatsuspoliitika — Koosolek

Viimati uuendatud: 17. mai 2026

## Lühikokkuvõte

Koosolek on koosolekute salvestamise ja protokollimise app, mis on disainitud **privaatsust säilitava** põhimõtte järgi. Sinu heli ja andmed jäävad sinu seadmesse — me ei saada midagi oma serverisse.

## Andmete kogumine

### Mis andmed jäävad sinu seadmesse (lokaalselt)

| Andmed | Kuidas kogutakse | Kus salvestatakse |
|---|---|---|
| Heli salvestus (WAV) | Mikrofoniga, sinu nõusolekul | Telefoni Documents kausta |
| Transkriptsioon | OpenAI API tagastab | SwiftData SQLite andmebaas |
| Protokoll | OpenAI API genereerib | SwiftData |
| Kalendri sündmused (vaadatakse) | iOS EventKit (sinu nõusolekul) | Ei salvestata äpis |
| Osalejad, action item'id | App'i poolt arvutatakse | SwiftData |
| OpenAI API võti | Sinu sisestus | iOS Keychain (krüpteeritud) |
| Seaded | Sinu valikud | UserDefaults |

### Mis andmed lähevad väljapoole sinu telefoni

#### 1. OpenAI API (tasuta ja Pro plaaniga, sinu enda kontoga)

Kui kasutad Tasuta või Pro plaani **sinu enda OpenAI API võtmega**:
- Heli (WAV-fail) saadetakse OpenAI Whisper API'le transkriptsiooniks
- Transkripti tekst saadetakse OpenAI GPT API'le protokolli koostamiseks
- Need toimingud käivad **otse sinu telefonilt OpenAI'le** — Koosoleku serverit ei kasutata
- OpenAI privaatsus: [openai.com/policies/privacy-policy](https://openai.com/policies/privacy-policy)

#### 2. Koosolek Cloud (kui kasutaja on Cloud plaani peal)

Kui kasutad Cloud plaani, saadame heli ja teksti **meie backend'i kaudu** OpenAI'le. See lisab ühe vahepealse serveri, kuid:
- Me **ei salvesta** sinu heli ega teksti pärast päringu lõpetamist
- Me **ei kasuta** sinu sisu kommertsotstarbel
- Me jälgime ainult kasutuse kogust (minutid) arvelduseks

#### 3. App Store Connect (Apple)

Apple jälgib oste, tellimusi, krahhe (anonüümselt). See on Apple'i poliitika, mitte meie.

#### 4. Tagasiside arendajale

Kui valid "Soovita äpi parandust" → "Saada e-mailiga":
- Sinu tekst, e-mail (kui sisestasid), äpi versioon, iOS versioon ja seadme mudel saadetakse aadressile appfix@vertex.ee
- Need on saadetud ainult **sinu vajutusega Mail composer'is**
- Me ei kasuta neid muudeks otstarveteks peale äpi parandamise

## Kalendri ligipääs

Kui annad kalendri ligipääsu, Koosolek loeb sinu järgmisi koosolekuid, et eel-täita protokolli andmeid (pealkiri, osalejad, aeg). Kalendrist loetud andmed:
- Jäävad ainult sinu seadmesse
- Lisatakse koosolekule **alles siis, kui sa koosoleku salvestad**
- Ei salvestata meie serverisse

Kalendrit saad muuta või lubatust eemaldada igal ajal iOS Settings'is.

## Meeldetuletuste ligipääs

Kui kasutad "Lisa Meeldetuletustesse" funktsiooni, lisatakse action item'id sinu Apple Meeldetuletustesse Loendi nimega "Koosolek". Lisamine toimub sinu seadmes, ilma välisühendusteta.

## Kasutaja õigused

Sul on alati õigus:

- **Vaadata** kõiki sinu andmeid äpis (kõik salvestused, transkriptsioonid, protokollid on äpis kättesaadavad)
- **Kustutada** üksikuid koosolekuid (swipe to delete) või kõiki korraga (Avaleht ⋯ menüü → "Kustuta kõik")
- **Eksportida** protokolle (PDF, RTF, Markdown)
- **Tühistada tellimust** App Store kaudu
- **Saada toetust** kirjutades aadressile appfix@vertex.ee

Apple'i poliitika kohaselt saad kogu äpi andmed kustutada, kui äpi telefonist desinstalleerid.

## Lapsed

Koosolek pole mõeldud alla 13-aastastele kasutajatele. Me ei kogu teadlikult andmeid alaealistelt.

## Muudatused

Privaatsuspoliitikat võime aeg-ajalt uuendada. Olulised muudatused teeme teatavaks äpi sees enne nende rakendamist.

## Kontakt

- **E-mail**: appfix@vertex.ee
- **App'i arendaja**: Vertex OÜ / Andro Kullerkupp, Eesti
- **Kohaldatav õigus**: Eesti Vabariik ja GDPR (EU)

GDPR-i kohaselt on sul õigus pöörduda kaebusega Eesti Andmekaitse Inspektsiooni poole: [aki.ee](https://www.aki.ee).
