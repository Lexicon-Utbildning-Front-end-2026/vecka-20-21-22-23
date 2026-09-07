# 🤝 Gruppkontrakt: [TEAMNAMN]

| Information | Detaljer |
| :--- | :--- |
| **Projekt** | Webbshoppen – Kundportalen (Fas 2) |
| **Period** | 21 september 2026 – 13 oktober 2026 (v. 39 – v. 42) |
| **Primär kommunikation** | Microsoft Teams |
| **Projektstyrning** | GitHub Projects |
| **Motto** | [Skriv ert gemensamma motto här, t.ex. "Lärande och samarbete framför prestige"] |
| **Referenser** | [PRD.md](file:///c:/docLocal/Lexicon/FE26/grupparbete/PRD.md) \| [ADR-mall](file:///c:/docLocal/Lexicon/FE26/grupparbete/docs/ADR-mall.md) \| [Domänordlista](file:///c:/docLocal/Lexicon/FE26/grupparbete/docs/GLOSSARY.md) |

---

## 🕒 1. Tid, Närvaro & Engagemang

För att skapa ett tryggt och förutsägbart arbetsklimat har vi kommit överens om följande:

* **Daily Standup:** Vi ses varje arbetsdag kl. **[09:15]** i vår kanal i **Teams**. Max 15 minuter där alla svarar på:
  1. *Vad gjorde jag igår?*
  2. *Vad ska jag göra idag?*
  3. *Har jag några hinder (blockers) där jag behöver hjälp?*
* **Kärntid:** Vi förväntas vara tillgängliga för samarbete, parprogrammering och snabba frågor i Teams mellan kl. **[09:00]** och **[16:00]**.
* **Frånvaro & Förhinder:** Om någon blir sjuk eller får förhinder ska detta meddelas i Teams senast kl. **[08:45]** (innan standup).
* **Ambitionsnivå i gruppen:**  
  *Exempel: [ ] "Vi fokuserar på att bygga en stabil MVP och se till att alla i gruppen förstår koden."*  
  *Exempel: [ ] "Vi siktar högt och vill utmana oss med avancerade moduler och molntjänster."*

---

## 🛠 2. Agilt Arbetssätt & Planering

Vi jobbar strukturerat för att behålla överblicken och undvika stress:

* **Sprintar:** Vi rekommenderar sprintar om **[5]** arbetsdagar (veckobaserade).
* **Sprint Planning:** Varje måndag kl. **[10:00]** går vi gemensamt igenom backloggen och fördelar veckans uppgifter.
* **Issues / Tickets:** Inget arbete påbörjas utan en tillhörande Issue på GitHub.
  * Varje Issue ska ha en tydlig beskrivning kopplad till [PRD.md](file:///c:/docLocal/Lexicon/FE26/grupparbete/PRD.md) samt en "Definition of Done".
* **Projektbräde:** Vi använder **GitHub Projects** och uppdaterar kolumnerna (*To Do, In Progress, In Review, Done*) i realtid.

---

## 🤖 3. AI-Policy & Kodkultur

Hur vi använder AI-verktyg på ett sätt som gynnar hela gruppens lärande:

* **Inriktning för AI-användning:**
  * [ ] **Rådgivande:** Vi använder AI som ett bollplank för logik och felsökning, men skriver koden manuellt.
  * [ ] **Generativ med full förståelse:** Vi använder AI för att generera kodblock, men den som checkar in koden ansvarar för att kunna förklara exakt vad den gör för resten av gruppen.
* **Skydd mot "AI-dumping":**
  * Ingen teammedlem får checka in stora AI-genererade kodsjok eller ändra applikationens grundarkitektur utan att först ha förankrat det med gruppen.
  * Den som pushar kod ska kunna förklara koden rad för rad för vem som helst i teamet på begäran.
* **Code Reviews:** Innan en Pull Request (PR) mergas till `main` ska minst **[1]** annan teammedlem aktivt granska och godkänna koden.
* **Kunskapsdelning (60-minutersregeln):** Om någon kör fast i mer än **[60]** minuter ber man om hjälp i Teams eller startar en parprogrammeringssession.

---

## 🌿 4. Git-strategi, Säkerhet & Miljövariabler

För att undvika trasig kod och läckta lösenord:

* **Branching:** Vi skapar alltid nya feature-branches från `main`.  
  *Namnstandard:* `feature/[issue-nr]-[kort-beskrivning]` (t.ex. `feature/12-search-filter`).
* **Inga Force Pushes:** Vi gör aldrig `git push --force` till delade branches. Eventuella merge-konflikter löses tillsammans i gruppen via delad skärm i Teams.
* **Säkerhet & Miljövariabler (`.env.local`):**
  * Vi pushar **ALDRIG** `.env.local` eller hemliga API-nycklar (t.ex. Clerk, Supabase, Stripe) till GitHub.
  * Den som lägger till en ny miljövariabel ansvarar för att uppdatera `.env.example` i repot och meddela gruppen i Teams.
* **Frekventa commits:** Vi pushar vår kod ofta (minst en gång per arbetsdag) i små, hanterbara PRs.

---

## 💬 5. Kommunikation & Eskaleringsplan (Om någon tystnar)

Vi lovar att bemöta varandra professionellt och schysst:

* **Feedback:** Vi ger konstruktiv feedback på koden, aldrig på person.
* **Beslut:** Vi strävar efter konsensus. Vid oenighet röstar vi, och vid dött lopp rådfrågar vi läraren.
* **Eskaleringsplan om en teammedlem uteblir utan förvarning (AWOL-trappan):**
  1. **Steg 1 (Kl. 10:00 efter utebliven standup):** Teamet skickar ett personligt DM i Teams för att stämma av läget.
  2. **Steg 2 (Efter lunch kl. 13:00):** Gruppen håller en kort avstämning: *"Hur påverkas sprinten?"*. Personens eventuella blockerande tickets pausas eller omfördelas så att ingen annan hindras i sitt arbete.
  3. **Steg 3 (Slutet av dagen eller nästa dags morgon utan kontakt):** Gruppen kontaktar handledare/lärare gemensamt via Teams för att få stöd och reda ut situationen.

---

## ✍️ Underskrifter / Bekräftelse

Genom att skriva under/bekräfta godkänner vi att arbeta enligt detta kontrakt:

* **Medlem 1:** [Namn] – [Datum]
* **Medlem 2:** [Namn] – [Datum]
* **Medlem 3:** [Namn] – [Datum]
* **Medlem 4:** [Namn] – [Datum]
* **Medlem 5:** [Namn] – [Datum]

---
*Detta kontrakt är ett levande dokument och kan revideras vid gruppens sprint-retrospectives om hela teamet är enigt.*
