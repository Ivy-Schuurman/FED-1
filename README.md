# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.





## Jij

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Auteur:
  Ivy Schuurman

  #### Je startniveau:
  Rood

  #### Je focus:
  Mijn focus ligt op beide een beetje, maar vooral op de surface plane
 
</details>





## Je website

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Je opdracht:
  De website van Ferrari, https://www.ferrari.com/en-NL 

  #### Screenshot(s) van de eerste pagina (small screen): 
  Home pagina 
  <img src="readme-images/home_pagina.png" width="375px" alt="De home pagina van de Ferrari website">

  #### Screenshot(s) van de tweede pagina (small screen):
  Pagina waar wordt verteld over de Ferrari F40  
  <img src="readme-images/ferrariF40_pagina.png" width="375px" alt="De detail pagina van de Ferrari F40">
 
</details>



## Toegankelijkheidstest 1/2 (week 1)

<details>
  <summary>uitwerken na test in 2<sup>e</sup> werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen:
  Bij het gebruiken van de screen reader van Windows ging het helemaal fout. De screen reader kon alleen het menu opnoemen en de andere
  delen van de pagina's werden niet meegenomen. De site heeft wel een eigen screen reader die de gebruiker kan instellen. 

  Hier de foto's van de WCAG checklist (eerste test):
  <img src="readme-images/pagina_1.jpg>" alt="Eerste pagina van de WCAG checklist"> 
  <img src="readme-images/pagina_2.jpg>" alt="Tweede pagina van de WCAG checklist"> 
  <img src="readme-images/pagina_3.jpg>" alt="Derde pagina van de WCAG checklist"> 
  <img src="readme-images/pagina_4.jpg>" alt="Vierde pagina van de WCAG checklist"> 
  <img src="readme-images/pagina_5.jpg>" alt="Vijfde pagina van de WCAG checklist"> 

</details>



## Breakdownschets (week 1)

<details>
  <summary>uitwerken na afloop 3<sup>e</sup> werkgroep</summary>

  ### de hele pagina: 
  <img src="readme-images/breakdown_home_pagina.png" width="375px" alt="breakdown schets van de hele home pagian">
  <img src="readme-images/breakdown_detail_pagina.png" width="375px" alt="breakdown schets van de hele detail pagian">

  ### dynamisch deel (home pagina): 
  <img src="readme-images/dynamische_home_1.png" width="375px" alt="breakdown van een dynamisch deel van de home pagina">
  <img src="readme-images/dynamische_home_2.png" width="375px" alt="breakdown van een dynamisch deel van de home pagina">

  ### dynamisch deel (detail pagina): 
  <img src="readme-images/dynamisch_detail.png" width="375px" alt="breakdown van nog een dynamisch deel van de detail pagina">

</details>





## Voortgang 1 (week 2)

<details>
  <summary>uitwerken voor 1<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  Het maken van de HTML van mijn website ging snel en makkelijk. Wel heb ik voor nu nog wat dingen weggelaten. Bijvoorbeeld de fotos van de gallerijen, 
  omdat ik nog niet weet of dit mijn micro interactie gaat worden en ik niet meer dan 40 fotos op één pagina wil waar ik dan niks mee doe. 


  ### Agenda voor meeting
  samen met je groepje opstellen

  |                |                    |                   |                  |
  | ---            | ---                | ---               | ---              |
  | Hoe geef je een| Wat doe ik met de  | Hoe maak ik het   |                  |
  | hamburger menu/| video delen van    | pop-up menu van   |                  |
  | gallerij/      | mijn website?      | de detail pagina? |                  |
  | carousel weer  |                    | detail pagina? Hoe|                  | 
  | in HTML?       |                    | zet ik dit in de  |                  |
  |                |                    | HTML?             |                  |
  | ...            | ...                | ...               | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - Maak gebruik van articles voor carousels
  - Detail element kan gebruikt worden voor het uitklappen van de footer -> is alleen niet geweldig voor vormgeving
  - Focus eerst op basis pagina voor HTML en CSS -> kijk daarna naar het klikbaar maken van buttons, etc. 
  - Snap je iets niet? probeer het dan gewoon en kijk bij het volgende feedback moment hoe het verbeterd kan worden

</details>





## Voortgang 2 (week 3)

<details>
  <summary>uitwerken voor 2<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  De CSS gaat een beetje langzaam, langzamer dan ik zou willen in iedergeval. Het is niet altijd even makkelijk voor mij om uit te vogelen welke properies ik 
  moet gebruiken en bij welk element ik deze dan moet toepassen. Het lukt mij wel, maar ik heb ook zeker heel wat stukken waar ik toch vast loop.
  (foto's volgen nog)


  ### Agenda voor meeting
  samen met je groepje opstellen

  |                |                    |                 |                   |
  | ---            | ---                | ---             | ---               |
  | Hoe maak ik de | Hoe haal ik de     | Ik heb hulp     | Ik heb hulp nodig |
  | buttons in de  | witte strepen op   | nodig bij het   | bij het maken van |
  | footer na?     | website weg?       | maken van       | de header (menu)  |  
  |                |                    | buttons         |                   |
  | ...            | ...                | ...             | ...               |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - Voor de buttons in de footer kijk of je gebruik kan maken van <details>, <before> en <after>
    -> <before> voor de icons
    -> <after> voor het plusje
  - Voor de nav in de footer kan je flex en flex-wrap gebruiken
  - Voor het weghalen van de witte strepen moet je de background-color van de gehele pagina aanpassen
  - Img folder moet nog geupdate worden op github, want je ziet nu niet de namen van de afbeeldingen

</details>





## Toegankelijkheidstest 2/2 (week 4)

<details>
  <summary>uitwerken na test in 9<sup>e</sup> werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen (geef ook aan wat er verbeterd is):
  De screen reader doet het veel beter. Hij gaat nu echt door de site heen in plaats van dat hij alleen blijft hangen bij de header van de pagina.
  Wel werkt de screen reader niet heel soepel, maar dit komt denk ik vooral door mijn onervarenheid met het gebruiken van een screen reader.

  Hier de foto's van de WCAG checklist (tweede test):
  <img src="readme-images/test_2_pagina_1.jpg>" alt="Eerste pagina van de WCAG checklist"> 
  <img src="readme-images/test_2_pagina_2.jpg>" alt="Tweede pagina van de WCAG checklist"> 
  <img src="readme-images/test_2_pagina_3.jpg>" alt="Derde pagina van de WCAG checklist"> 
  <img src="readme-images/test_2_pagina_4.jpg>" alt="Vierde pagina van de WCAG checklist"> 
  <img src="readme-images/test_2_pagina_5.jpg>" alt="Vijfde pagina van de WCAG checklist"> 

</details>





## Voortgang 3 (week 4)

<details>
  <summary>uitwerken voor 3<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  Ben bijna helemaal klaar met mijn CSS, maar ik heb hier wel nog steeds moeite mee.


  ### Agenda voor meeting
  samen met je groepje opstellen

  |                |                     |                   |                  |                      |                      |           |             |
  | ---            | ---                 | ---               | ---              | ---                  | ---                  | ---       | ---         |   
  | Home section 1:| Home section 2:     | Hamburger menu    | Gallery: tekst & | Detail pagina:       | Achive button        | H1 & logo | links & svg |
  | video + tekst +| afbeelding + buttons| (niet werkende)   | buttons          | gap bij laatste twee | => waar is de tekst? |           |             |
  | buttons        | + link              | detail pagina     |                  | afbeeldingen         |                      |           |             |
  | ...            | ...                 | ...               | ...              | ---                  | ---                  | ---       | ---         |

  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - Section 1: gebruik grid -> columns & rows, zet buttons in een article, geef video volledige breedte, H2/p in een div zetten en zet de buttons in een ul
  - Section 2: haal padding bij de afbeelding weg, zet buttons in een ul en pas hier flexbox op toe => row, space between (articles) en 0 padding
  - Gebruik voor tekst kleur custom properties (handig voor light/dark mode)
  - Hamburger menu: flexbox toepassen, onderste buttons in een div
  - Gallery: position voor p is goed, werk met bottom, left, rigth & top voor positionering
  - Detail pagina: geef onderste foto's een width van 100%
  - Bij links zet de svg achter de tekst
  - Detail pagina: titels met een streepje => gebruik een lege span

</details>





## Eindgesprek (week 5)

<details>
  <summary>uitwerken voor eindgesprek</summary>

  ### Je uitkomst - karakteristiek screenshots:
  <img src="readme-images/" width="375px" alt="uitomst opdracht 1">
  <img src="readme-images/" width="375px" alt="uitomst opdracht 2">


  ### Dit ging goed/Heb ik geleerd: 
  Korte omschrijving met plaatjes
  Bij mij ging verliep het maken van de HTML heel soepel en ben ook niet tegen problemen aangelopen. Moest soms hier en daar wat onderdelen aanpassen/weghalen/toevoegen
  voor mijn CSS, maar dat lukte allemaal prima. JavaScript verliep niet altijd even makkelijk maar is wel gelukt, vooral door te kijken naar code die ik zelf al eerder had geschreven en bij het hamburger menu heeft het vooral geholpen dat ik de opdracht ervoor in de les had gemaakt. Ik ben wel blij dat het mij is gelukt om light mode toe te passe (al dan wel met hulp), ondanks dat het alleen op de detail pagina werkt.   
  <img src="readme-images/top_1.png" width="375px" alt="top 1">
  <img src="readme-images/top_2.png" width="375px" alt="top 2">
  <img src="readme-images/top_3.png" width="375px" alt="top 3">

  ### Dit was lastig/Is niet gelukt:
  Korte omschrijving met plaatjes
  Ik had heel wat moeite met het maken van de CSS, er zijn nu steeds aan paar onderdelen die niet helemaal werken zoals die horen te werk of zoals ik wou dat deze onderdelen werkte. Dit zijn bijvoorbeeld de scroll animatie, deze werkt niet zoals hij zou moeten werken. Het hamburger menu werk ook niet helemaal zoals ik zou willen, maar het werkt wel. 
  <img src="readme-images/bummer_1.png" width="375px" alt="bummer 1">
  <img src="readme-images/bummer_2.png" width="375px" alt="bummer 2">
</details>





## Bronnenlijst

<details open>
  <summary>continu bijhouden terwijl je werkt</summary>

  Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg). 
  Nb. ChatGpT en andere AI horen er ook bij.
  Nb. Vermeld de bronnen ook in je code.

  1. ChatGPT heb ik gebruikt bij mijn animatie en scroll animatie, maar puur en alleen voor het oplossen van problemen waar ik tegen aanliep,
     controleren waar ik een fout heb gemaakt in mijn code en voor als ik iets niet begreep. Ook heb ik dit gebruikt om mijn probleem met light mode te achterhalen, maar dit is mij uiteindelijk gelukt zelf op te lossen. Hier is de link naar de chat: https://chatgpt.com/share/67557761-1dd4-8000-aa46-a0488c8b5cf3 
  2. bron 2
  3. ...

</details>