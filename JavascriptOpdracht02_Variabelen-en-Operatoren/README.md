# Javascript 
## Opdracht 02: Variabelen en eenvoudige berekeningen 
Oefening: Maak een programma dat het omtrek en oppervlakte van een rechthoek berekent.

## **Inhoud:** 
- **Variabelen:** Leerlingen leren variabelen aanmaken en waarden toewijzen. 
- **Rekenkundige operatoren:** Leerlingen leren basisrekeningen uitvoeren zoals optellen en vermenigvuldigen.
- **Invoer en validatie:** Leerlingen leren hoe ze invoer van gebruikers kunnen ophalen en validaties kunnen uitvoeren.
- **Controle:** controleer of de invoer geldig is

## Werkwijze
1. **Download** de volledige **repository**,
2. **Schrijf je code** in het juiste bestand,
    - Stap 1: Maak een HTML-pagina voor de invoer
    - Stap 2: Schrijf de functie bereken()
    - Stap 3: Controleer of de invoer geldig is (T!P: IsNAN)
    - Stap 4: Voer de berekeningen uit
    - Stap 5: Toon het resultaat   
3. **Test** je code,
4. **Documenteer** je code,
4. **Upload** je volldige repository in de **aangegeven uploadmap**,
5. Vul de **zelfevalautie** in.

##  Startcode HTML

```html
<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bereken Omtrek en Oppervlakte van een Rechthoek</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        input {
            margin: 10px;
            padding: 8px;
            width: 100px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
        h2 {
            color: #333;
        }
    </style>
</head>
<body>
    <h1>Bereken de Omtrek en Oppervlakte van een Rechthoek</h1>
    
    <label for="lengte">Lengte:</label>
    <input type="number" id="lengte" placeholder="Voer lengte in">
    
    <label for="breedte">Breedte:</label>
    <input type="number" id="breedte" placeholder="Voer breedte in">
    
    <button onclick="bereken()">Bereken</button>
    
    <h2 id="resultaat"></h2>

    <script>

    </script>

</body>
</html>

```
## Veel Succes!