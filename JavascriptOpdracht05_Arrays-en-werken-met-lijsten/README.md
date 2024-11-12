# Javascript
## Opdracht 05: Arrays en werken met lijsten
> **LEERDOELEN:**  
> Je begrijpt hoe je arrays kunt maken en gebruiken in JavaScript.  
> Je leert hoe je door een lijst kunt lopen en gegevens kunt toevoegen, verwijderen, of aanpassen.  
> Je ontwikkelt je probleemoplossend vermogen door met data in arrays te werken.

### Doel van de opdracht
In deze opdracht ga je leren werken met arrays, oftewel lijsten. Je gaat een boodschappenlijst-app maken waarin je items kunt toevoegen, verwijderen en bekijken.

### Wat ga je doen?
Je gaat een interactieve boodschappenlijst maken waarin je nieuwe items kunt toevoegen aan een lijst, items kunt verwijderen en de lijst kunt weergeven. Dit helpt je om te begrijpen hoe je arrays kunt beheren in JavaScript.

### Stappen om de opdracht uit te voeren:

1. **HTML Opzetten:**
   - Maak een nieuwe HTML-pagina en voeg de volgende elementen toe:
     - Een titel voor de app (bijvoorbeeld "Boodschappenlijst").
     - Een inputveld waarin de gebruiker een item kan invoeren.
     - Een knop om het item aan de lijst toe te voegen.
     - Een knop om een item van de lijst te verwijderen.
     - Een plek om de lijst met items weer te geven (bijvoorbeeld een ongeordende lijst met `id="boodschappenlijst"`).

2. **JavaScript Functies Creëren:**
   - Schrijf JavaScript-functies voor de volgende acties:
     - **Item toevoegen**: Voeg het item uit het inputveld toe aan de array en update de weergave van de lijst.
     - **Item verwijderen**: Verwijder een specifiek item uit de array (bijvoorbeeld door het laatste item te verwijderen of een specifieke naam).
     - **Lijst weergeven**: Toon de volledige boodschappenlijst in de HTML, zodat de gebruiker de lijst altijd up-to-date kan zien.

3. **Feedback Geven:**
   - Zorg ervoor dat de feedback duidelijk en begrijpelijk is voor de gebruiker:
     - Toon een bericht bij elke actie, zoals “Item toegevoegd” of “Item verwijderd”.
     - Zorg ervoor dat de lijst altijd de meest recente versie van de items toont.

### Werkwijze
1. **Download** de volledige **repository**.
2. **Schrijf je code** in het juiste bestand.
3. **Test** je code.
4. **Documenteer** je code.
5. **Upload** je volledige repository in de **aangegeven uploadmap**.
6. Vul de **zelfevaluatie** in.

## Startcode HTML

```html
<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boodschappenlijst</title>
</head>
<body>
    <h2>Boodschappenlijst</h2>
    <input type="text" id="item" placeholder="Voer een item in">
    <button onclick="voegItemToe()">Toevoegen</button>
    <button onclick="verwijderLaatsteItem()">Verwijderen</button>

    <ul id="boodschappenlijst"></ul>

    <script>

    </script>
</body>
</html>
```
# ZELFEVALUATIE 05
**Doel:** Een interactieve boodschappenlijst maken waarin de gebruiker items kan toevoegen en verwijderen met behulp van arrays.

| **Criteria**                            | **Beoordeling (1-5)** | **Opmerkingen**                         |
|-----------------------------------------|------------------------|-----------------------------------------|
| **Gebruik van arrays**                  |                        | Zijn arrays correct toegepast?          |
| **Toevoegen en verwijderen van items**  |                        | Werken de functies zoals bedoeld?       |
| **Feedback aan gebruiker**              |                        | Is de feedback duidelijk en relevant?   |
| **Functionaliteit van de lijstweergave**|                        | Wordt de lijst correct weergegeven?     |
| **Algehele gebruikerservaring**         |                        | Hoe gebruiksvriendelijk is de app?      |

### Evaluatiewijze:
- **1**: Onvoldoende: Ik kan dit onderdeel niet uitvoeren.
- **2**: Voldoende: Ik kan dit onderdeel uitvoeren.
- **3**: Goed.
- **4**: Zeer goed: Ik kan dit met opzoekingswerk.
- **5**: Uitstekend: Ik kan dit zonder opzoekingswerk.

---

**Instructies voor het invullen van de Zelfevaluatie:**

1. **Beoordeel elk criterium** door een cijfer van 1 tot 5 te geven:
   - **1**: Onvoldoende – Ik kan dit onderdeel niet uitvoeren.
   - **2**: Voldoende – Ik kan dit onderdeel uitvoeren.
   - **3**: Goed.
   - **4**: Zeer goed – Ik kan dit met opzoekingswerk.
   - **5**: Uitstekend – Ik kan dit zonder opzoekingswerk.

2. **Voeg opmerkingen toe** bij elk criterium om meer inzicht te geven in je prestatie en mogelijke verbeterpunten.

3. **Bepaal je gemiddelde score** om een totaalbeeld te krijgen van je prestatie en geef advies voor verdere verbetering.

---

**Voorbeeld van een ingevulde Zelfevaluatie:**

| **Criteria**                            | **Beoordeling (1-5)** | **Opmerkingen**                         |
|-----------------------------------------|------------------------|-----------------------------------------|
| **Gebruik van arrays**                  | 4                      | De array werkt goed, maar ik wil leren hoe ik items kan sorteren. |
| **Toevoegen en verwijderen van items**  | 5                      | Alles werkt zoals bedoeld, zonder fouten. |
| **Feedback aan gebruiker**              | 4                      | Duidelijke feedback, maar ik wil graag meer gedetailleerde meldingen toevoegen. |
| **Functionaliteit van de lijstweergave**| 3                      | De lijst werkt, maar ik moet werken aan de styling. |
| **Algehele gebruikerservaring**         | 4                      | Gebruiksvriendelijk, maar ik wil knoppen voor extra functies toevoegen. |

**Gemiddelde score:** 4.0

**Advies voor verbetering:**
- Experimenteer met het sorteren van items in de array.
- Voeg meer gedetailleerde feedbackmeldingen toe.
- Werk aan de styling van de lijstweergave om de app aantrekkelijker te maken.
- Voeg extra functies toe, zoals een knop om alle items te wissen.

---

**Succes!** Ga door met oefenen om je vaardigheden in JavaScript en werken met arrays verder te ontwikkelen!
