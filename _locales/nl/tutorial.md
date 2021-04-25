# Tutorial
## Step 1
Tijdens deze tutorial gaan we een propeller op het scherm  laten verschijnen. Om te beginnen hebben we enkel de ``||basic:altijd||`` blok nodig. Je kunt een blok verwijderen door deze naar de toolbox links te slepen. 
Je kunt dit nu doen voor de ``||basic:starten||`` blok. 
## Step 2
Nu kunnen een blok invoegen die led lichtjes laat zien. Deze vindt je in de ``||basic:basis||`` groep. Merk op dat de kleur van ``||basic:toonleds||`` blauw is. Dit geeft ook een indicator in welke groep je een blok moet gaan zoeken.
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```
## Step 3
Laat nu een lichtje branden door het middelste knopje aan te klikken. Je kunt het lichtje laten stoppen met branden door deze opnieuw aan te klikken.
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . # . .
        . . . . .
        . . . . .
        `)
})
```
## Step  4 
We kunnen nu een kruis maken door op de 2 led lichtjes boven, onder, links en rechts van het middelpunt te klikken.
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        . . # . .
        # # # # #
        . . # . .
        . . # . .
        `)
})
```
## Step 5
Om een mooie propeller te maken moeten we de lichtjes met de klok mee verplaatsen. We kunnen dit doen door op de led lichtjes te klikken om deze te laten uitgaan en dan op het knopje er naast te klikken met de klok mee.
Bijvoorbeeld naar rechts voor de bovenste 2, naar onder voor de rechter 2 lichtjes, enzovoort...
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . # .
        # # . # .
        . . # . .
        . # . # #
        . # . . .
        `)
})
```
## Step 5
Goed gedaan! Als je een iets uitdagendere codeer oefening wilt over de propeller kun je onze andere tutorial uitproberen.