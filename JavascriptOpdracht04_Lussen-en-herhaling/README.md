# Javascript
## Opdracht 04: Lussen en herhaling
> **LEERDOELEN:**  
> Je begrijpt hoe lussen (loops) werken in JavaScript.  
> Je leert hoe je acties kunt herhalen totdat aan een bepaalde voorwaarde is voldaan.  
> Je ontwikkelt je probleemoplossend vermogen door feedback te geven op basis van de input van de gebruiker.

### Doel van de opdracht
In deze opdracht ga je leren hoe je lussen kunt gebruiken om acties te herhalen. Je gaat een eenvoudig spel maken waarin de gebruiker een getal probeert te raden. Door de lus krijgt de gebruiker meerdere kansen om het juiste antwoord te vinden en ontvangt hij feedback na elke poging.

### Wat ga je doen?
Je gaat een "Raad het getal"-spel maken waarbij de gebruiker een willekeurig gekozen getal tussen 1 en 100 probeert te raden. Het spel geeft de gebruiker feedback of het getal te hoog of te laag is, en houdt bij hoeveel pogingen de gebruiker nog heeft.

### Stappen om de opdracht uit te voeren:

1. **HTML Opzetten:**
   - Maak een nieuwe HTML-pagina en voeg de volgende elementen toe:
     - Een titel voor het spel (bijvoorbeeld "Raad het Getal Spel").
     - Een inputveld waarin de gebruiker een getal kan invoeren.
     - Een knop om de gok in te sturen.
     - Een plek om het resultaat en de feedback weer te geven (bijvoorbeeld een paragraaf met `id="resultaat"`).

2. **JavaScript Functie Creëren:**
   - Schrijf een JavaScript-functie `startSpel` die wordt uitgevoerd wanneer de gebruiker op de "Gok!"-knop klikt.
   - De functie moet:
     - Een willekeurig getal genereren tussen 1 en 100 (dit wordt het geheime getal).
     - Het aantal toegestane pogingen bijhouden (bijvoorbeeld 5).
     - In een `while`-lus herhaaldelijk de gok van de gebruiker ophalen en controleren:
       - Als de gok correct is, toon een succesbericht.
       - Als de gok te hoog of te laag is, geef feedback aan de gebruiker.
       - Als het aantal pogingen op is, toon een verliesbericht en het juiste getal.

3. **Feedback Geven:**
   - Zorg ervoor dat de feedback duidelijk en begrijpelijk is voor de gebruiker:
     - Toon of het getal te hoog of te laag is.
     - Toon het aantal resterende pogingen.
     - Geef een eindboodschap wanneer het getal is geraden of het aantal pogingen is opgebruikt.

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
    <title>Raad het Getal Spel</title>
</head>
<body>
    <h2>Raad het Getal Spel</h2>
    <p>Raad het geheime getal tussen 1 en 100. Je hebt meerdere pogingen!</p>

    <input type="number" id="guess" placeholder="Voer je gok in">
    <button onclick="startSpel()">Gok!</button>

    <p id="resultaat"></p>

    <script>

    </script>
</body>
</html>
```
# ZELFEVALUATIE 04
**Doel:** Een spel maken waarin de gebruiker meerdere pogingen krijgt om een getal te raden met duidelijke feedback na elke poging.

| **Criteria**                            | **Beoordeling (1-5)** | **Opmerkingen**                         |
|-----------------------------------------|-----------------------|-----------------------------------------|
| **Gebruik van loops (while-lus)**       |                       | Is de loop correct toegepast?           |
| **Feedback aan gebruiker**              |                       | Is de feedback duidelijk en relevant?   |
| **Functionele gebruikersinput**         |                       | Werkt het verzamelen van input zoals bedoeld? |
| **Creativiteit en gebruikerservaring**  |                       | Is de feedback leuk en interactief?     |
| **Algehele gebruikerservaring**         |                       | Hoe gebruiksvriendelijk is het spel?    |

### Evaluatiewijze:
- **1**: Onvoldoende: Ik kan dit onderdeel niet uitvoeren.
- **2**: Voldoende: Ik kan dit onderdeel uitvoeren.
- **3**: Goed.
- **4**: Zeer goed: Ik kan dit met opzoekingswerk.
- **5**: Uitstekend: Ik kan dit zonder opzoekingswerk.
