# DEVOPS-2 - 02 - Versiebeheer - Taak 03

## Git Checkout

## Uitleg

Tot nu toe heb je veel gecommit, je code gepushed naar de repository op github maar nog weinig gebruik gemaakt van de vele mogelijkheden die Git je nog meer biedt.

In deze taak gaan we een commit _uitchecken_. Hiermee kun je de code zoals die was toen je een bepaalde commit maakte weer terughalen. 

Dit doe je via de terminal door het onderstaande commando uit te voeren:
```cmd
git checkout <commit hash>
```
:zap: LETOP: Als je dit doet krijg je je code terug zoals die eruit zag op het moment dat je de commit maakte. De undo informatie die je editor voor je bijhoudt krijgt je niet terug. <kbd>CTRL</kbd>+<kbd>Z</kbd> / <kbd>CTRL</kbd>+<kbd>Y</kbd> werkt dus niet zoals je misschien denkt. Maak dus zoveel mogelijk kleine commits tijdens het werken zodat je altijd naar dat punt terug kunt keren.

## Leerdoelen

1. Ik kan een commit uitchecken via de terminal of met de Gitgraph extensie.

## Opdracht

1.  Zorg ervoor dat je dit README.md bestand geopend hebt in VS Code (met eventueel de leesbare preview ernaast) en voer onderstaande git commando uit in de terminal:
    ```cmd
        git checkout HASH?
    ```
2. Gelukt! Je hebt nu een 'oudere' versie van de `README.md` uigechecked. In dit geval bevat de oudere versie een tweede opdracht: Toon de commits van deze repository in je terminal of via de Gitgraph extenstie. Als het goed is zie je dat de `HEAD` niet meer wijst naar de laatste commit maar dat deze nu wijst naar de commit die je net hebt uitgecheckt! 
3. Voer onderstaande commando uit in de terminal om weer terug te gaan naar de commit die je had uitgecheckt voor je opdracht 1 uitvoerde.
    ```cmd
    git checkout -
    ```

## Eindresultaat



## Bronnen