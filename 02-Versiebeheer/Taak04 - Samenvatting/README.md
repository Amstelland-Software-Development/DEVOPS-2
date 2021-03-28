# DEVOPS-2 - 02 - Versiebeheer - Taak 04

## Samenvatting

## Uitleg

Ok, dus we hebben nu gezien dat je in de tijdlijn van commits elke commit terug kan halen via `git checkout`. 

Even een korte samenvatting van de nieuwe termen die we in voorgaande taken zijn tegengekomen, zie onderstaande output van `git log --pretty=oneline` in de terminal:

![](img/git-log-terminal.png)

* **Commit Hash**: Unieke reeks cijfers en letters die hoort bij een commit.
* **Commit Message**: In het grijs. Geeft kort en bondig weer wat er in code die bij die commit hoort is veranderd.
* **HEAD**: In het blauw. De **HEAD** geeft aan welke commit op dit moment is uitgecheckt.

> :zap: Zo'n lijst van commits wordt ook wel een _boom_ (tree) genoemd. De HEAD wijst standaard naar de laatste commit, oftewel de top van de boom. Als je een eerder gemaakte commit uitcheckt dan verplaatst de HEAD zich naar die commit en bevindt Git zich in een _DETACHED HEAD state_. In de terminal krijg je een waarschuwing en bij Gitgraph moet je expliciet toestemming geven daarvoor. 

### Gitgraph checkout

In onderstaande gif zie je de handelingen om de checkout van een commit te doen in Gitgraph. De plaats van de HEAD wordt getoond als een leeg blauw bolletje in de interface. In de praktijk zal je meer bezig zijn binnen de interface die VS code aanbiedt om om te gaan met Git dan dat je via de terminal werkt maar het is natuurlijk aan jou om te kiezen hoe je het liefst werkt.

![](img/git-gitgraph-checkout.gif)

## Leerdoelen

1. Ik weet wat een Commit Hash en dat deze uniek is
2. Ik weet wat de HEAD is wat deze aangeeft in `git log`
3. Ik kan via de interface van Git Graph een commit uitchecken
## Opdracht

1. Zorg ervoor dat je een idee hebt bij de verschillende termen zoals die in deze samenvatting genoemd zijn.

## Eindresultaat



## Bronnen