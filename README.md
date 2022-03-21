# 👀 Keep Users in Control 
Activity Diagram voor Coding the Curbs

## 👶🏼 User Story
Als potenciële partner, wil ik een lijst met smartzones op de website zien, zodat ik weet wat de functie zijn van smartzones.

## 🔥 Activity Diagram
### Wireflow
![Wireflow](https://github.com/M4TThys123/keep-users-in-control-activity-diagram/blob/main/assets/wirefow.JPG)

### Controll Flow
![Controll Flow](https://github.com/M4TThys123/keep-users-in-control-activity-diagram/blob/main/assets/Activity%20Diagram.JPG)

## Digial Version
![Final Version](https://github.com/M4TThys123/Keep-Users-in-Control-Activity-Diagram/blob/main/assets/Activity%20Diagram.png){ width=100% }


## 👨🏼‍💻 Uitleg pseudo-code 
Zodra de pagina wordt geladen komen we aan bij de **Empty state**. Tijdens deze state wordt getData uitgevoed, vervolgens verandert deze state naar loading. Dat zie je terug in mijn state.js/state(loading). 

Bij de **getData** worden de fetch(data) clean(data) en store(data) uitgevoerd, daarna word de render(data) uitgevoerd en dan verandered de state naar state(loaded). 

Bij **interactie** op de pagina word je doormiddl van een (click) via router.js/handleRoute()terug verwezen naar api.js/getData. Indien er iets fout gaat bij het ophalen van de data kom je bij de state.js/state(err), dit is een foutmelding pagina.

## 🦹‍♂️ Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
