# Python Oefeningen

## If else oefeningen

- Maak de oefeningen zodat je aan de gebruiker om invoer vraagt:

- 2 getallen, druk "Gelijk" af als deze gelijk zijn anders "Niet gelijk".
> getal1= input("geef getal 1: ")  
> getal2= input("geef getal 2: ")  
> if getal1 == getal2:  
>    print("Gelijk!")  
> else:  
>    print("Niet gelijk")  

- een getal tussen 50(inclusief) en 100(inclusief). Indien juist druk je "Ok" af anders "Niet Ok".
> getal1= input("geef getal tussen 50 en 100: ")  
> if getal1 >= 50 and getal1 <= 100 :  
>    print("OK!")  
> else:  
>    print("Niet OK!")  

- een getal en afdrukt of het even of oneven is.
> getal1= input("geef een getal in: ")  
> if (getal1 % 2 == 0):  
>    print("even")  
> else:  
>    print("oneven")  

- 3 getallen en druk het kleinste getal af.
> getal1= input("geef een getal1 in: ")  
> getal2= input("geef een getal2 in: ")  
> getal3= input("geef een getal3 in: ")  
> nums = [getal1, getal2, getal3]  
> print ("kleinste getal: ",min(nums))  

- 2 getallen tussen 0 en 10(beide incl). Als minstens 1 van de 2 getalen 8 of hoger is druk dan "OK" af, met uitzondering dat als 1 van de 2 getallen 2 of lager is, druk dan "Niet OK" af. Als beide getallen tussen 2 en 8 zijn, druk dan "Bijna OK" af.
>getal1= input("geef een getal1 in: ")  
>getal2= input("geef een getal2 in: ")  
>if getal1 <= 2 or getal2 <= 2:  
>    print("niet OK!")  
> elif getal1 >= 8 or getal2 >= 8:  
>    print("OK!")  
> elif getal1>2 and getal1<8 and getal2>2 and getal2<8:  
>    print("bijna OK!")  

## While en For oefeningen

BeFit is een bedrijf dat afslank producten verkoopt aan personen ouder dan 18 jaar.
Omdat heel veel mensen zich baseren op BMI hebben ze besloten om een BMI applicatie te
schrijven

Maak een programma dat de gegevens voor de BMI berekening van 3 personen vraagt.
(3 personen want BeFit hun business analist vond dit het beste voor het meeste rendement te behalen, vertrouw de analist hier op)
Van deze personen worden de volgende gegevens verwacht:
1. Naam
2. Leeftijd
3. Gewicht in kilogram
4. Lengte in meters

De gegevens zijn **enkel geldig** voor personen **ouder dan 18 jaar**, **indien** men een leeftijd **jonger als 18** invullen dan **vraag je opnieuw naar de gegevens** (druk ook een tekst af waarop duidelijk staat dat het enkel werkt voor personen van 18 of ouder en dat ze opnieuw de gegevens moeten invullen)
Het bmi wordt berekent door: **_Gewicht in kilogram / (Lengte in meters * Lengte in meters)_**
Omdat BeFit corrupt is en hun afslank producten willen verkopen, verhogen zij de bmi van
personen **ouder dan 30 (inclusief) met 5%** en **ouder dan 50 (inclusief) met 10%**.
Druk de naam en bmi af van deze 3 personen.
Omdat de persoon met de laagste bmi waarschijnlijk geen afslank producten wilt kopen, druk je nog af dat degene met de laagste bmi een korting krijgt van 15% bij zijn volgende aankoop.

#### Tips:
- **_Maak de oefening eerst voor 1 persoon._**
- Declareer en instantieer eerst de variabelen die we nodig hebben om de gegevens van de
persoon bij te houden.
- Gebruik een **while** voor de logica van het ingeven van de leeftijd (leeftijd moet
ouder dan 18 zijn).
- Gebruik een **elif** voor de bmi modificatie gebaseerd op leeftijd te bepalen
- Gebruik een **for loop** om te limiteren tot 3 personen
- Gebruik een **elif** om te bepalen of de gegevens van persoon 1, 2 of 3
ingevuld moet worden.

## Function oefeningen

1. Maak een functie die een parameter aanneemt en geef aan of deze positief of negatief is
door een boolean terug te geven.
2. Maak een functie die een parameter aanneemt en meldt of deze 0 is of niet.
3. Maak een functie die twee getallen aanneemt en de grootste waarde returned.
4. Maak een functie die twee getallen aanneemt en de laagste waarde returned.
5. Maak een functie die drie getallen aanneemt en de grootste waarde returned.
6. Maak een functie die drie getallen aanneemt en de kleinste waarde returned.
7. Maak een functie genaamd rollDice () die een getal van 1 tot 6 terug geeft.
9. Gebruik de functie van de dobbelstenen om 1 miljoen keer te gooien. Tel hoe vaak elk
nummer gegooid werd.
Bereken hiervan het percentage, was dit voor alle nummers ongeveer hetzelfde?
(aantal keer dat het voorkomt delen door 10_000)
