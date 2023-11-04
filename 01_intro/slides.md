---
marp: true
theme: gaia
color: #000
colorSecondary: #333
backgroundColor: #fff
style: |
    section.lead h1 {
    text-align: center;
    }

---
<!-- _class: lead -->
# Techniczne aspekty i role w projekcie

---
<!-- _class: lead -->
## Podstawowe pytania
<br />

- Co chcemy stworzyć (what?),
- W jakim celu chcemy to stworzyć (why?),
- W jaki sposób chcemy to stworzyć (how?),
- następnym kroki: design doc oraz UX/UI mockupy (patrz wstęp).

---
<!-- _class: lead -->
## Pamiętaj

Nie od razu możesz mieć idealny proces i narzędzia, co każdą iterację staraj się poprawiać co i jak pracujecie jako team. Kluczowe są retrospektywy!

---
<!-- _class: lead -->
## Metody wytwarzania oprogramowania
<br>

Szeroko rozumiany Agile-a:
- Kanban ([prokanban](https://prokanban.org/the-kanban-guide/)) lub SCRUM ([book](https://www.infoq.com/minibooks/scrum-xp-from-the-trenches-2/));
- Długość cyklu - najlepiej 1 tydzień.

---
<!-- _class: lead -->
## Narzędzia
<br />

Trackowanie zadań oraz WIP:

- YouTrack
- Github projects
- JIRA
- ClickUp

---
<!-- _class: lead -->
# Narzędzia
<br />

Komunikacja:

- Praca z tablicą zadań;
- chat (slack/discord);
- regularne spotkania: project meetings, daily standups, pairing sessions.

---
<!-- _class: lead -->
## Teams
<br>

- [**Product teams** vs feature teams](https://www.svpg.com/product-vs-feature-teams/),
- Organizacja zespołów (patrze [team topologies](https://teamtopologies.com/key-concepts)).

---
<!-- _class: lead -->
## Metoda dostarczania nowych wersji
<br />

Jak najszybciej: Continuous Deployment!

- mnogość rozwiązań CI/CD,
- Gitlab,
- Github.

---
<!-- _class: lead -->
## Podstawowa architektura aplikacji
<br />

- Wstępne ustalenie stacku technologicznego,
- Sposób udostępniania aplikacji użytkownikom,
- Monolit vs Mikroserwisy,
- -&gt; architektura (draw.io),
- -&gt; design doc.

---
<!-- _class: lead -->
## Skalowalność
<br />

- Czy spodziewamy się zmiennej ilości użytkowników?
- Czy zmienność może mieć charakter okresowy, czy raczej będzie to jednorodny trend?
- Czy potrzebujemy niezależnego skalowania komponentów aplikacji?
- Napkin math &amp; perf testing

-&gt; design doc

---
<!-- _class: lead -->
## Plan
<br />

Ma wpływ na architekturę aplikacji:

- v1/v2,
- Jakie funkcjonalności najpierw damy do rąk klientom...
- Jakie decyzje tech chcemy opóźnić?

---
<!-- _class: lead -->
## Elementy aplikacji
<br />

Klasyczne:

- Frontend,
- Backend,
- Bazy Danych,
- Warstwa serwerowa,
- Warstwa komunikacji.

---
<!-- _class: lead -->
# Podział na role


---
<!-- _class: lead -->
## Podział na role

Podstawa ([wartości](https://gist.github.com/adamwiggins/5687294)):

- You own your inputs,
- Make it real,
- DRI,
- Do-ocracy,
- Drum-beat comes from people doing the most of the work.

---
<!-- _class: lead -->
## Role w projekcie
<br />

Przykład:

- Team/Squad lead,
- Product manager,
- UX/UI designer
- Frontend/Mob developer,
- Backend developer.

---
<!-- _class: lead -->
## Dziękuję za uwagę
<br />
