---
Title: Laddningstid
Description: Det här är rapport
Template: analysis
---
# Absolut laddningstid
I denna rapport redovisas resultaten från en undersökning av absolut laddningstid för tre svenska kommuners hemsidor.

## Bakgrund
En hemsida består av en ansamling av filer som transporteras till en klient på förfrågan och visas med ändamålsenlig mjukvara. För att öka en sidas absoluta laddningstid finns en oslagbar metod, att minska mängden information som skickas. Man måste då värdera informationen och göra antaganden om hur den kommer att användas. Absolut laddningstid är tiden det tar för sidan att leverera sitt material, oberoende av storleken på materialet.

## Urval
Undersökningen har genomförts på tre svenska kommuners hemsidor, Kiruna, Trelleborg och Stockholm stad. 

## Metod
Varje sida har laddats om sex gånger för att få fram ett snittvärde. Innan varje testrunda gjordes ett test för att mäta nedladdningshastighet och uppladdningshastighet med hjälp av speedtest.net. Webbläsaren som användes var google chrome. 
Resultaten kompletteras med ett betyg från Google Pagespeed insights.

## Resultat
        
    Nedl. (Mbps)	Uppl. (Mbps)    Stockholm(ms)	Kiruna(ms)	Trelleborg(ms)
            5.11	        2.06	         6802        59356	          2150
            3.71	        2.09	        26818	    117333	          1769
           10.49	        2.12	        27247	     40803	          5247
            3.94	        3.11	        37205	     94875	          1063
            3.83	        3.15	        37802	     54010	          1148
            2.93	        3.34	        51378	      2399	          1131
    
               5  	        2,65	        31209	     71463	          2085

### Stockholm stad
#### https://start.stockholm
Stockholm stads hemsida hade en genomsnittlig laddningstid på 31 sekunder. Sämsta tid var 51 sekunder och bästa tid var 7 sekunder.

    GPI mobil: 56/100
    GPI dator: 80/100
    Total filstorlek: 2.7 MB

### Kiruna kommun
#### https://www.kiruna.se
Kiruna kommuns hemsida hade en genomsnittlig laddningstid på 71 sekunder. Sämsta tid var 117 sekunder och bästa tid 41 sekunder.

    GPI mobil: 20/100
    GPI dator: 48/100
    Total filstorlek: 31.8 MB

### Trelleborgs kommun
#### https://www.trelleborg.se/
Trelleborgs kommuns hemsida hade en genomsnittlig laddningstid på 2 sekunder. Sämsta tid var 5 sekunder och bästa tid 1 sekund.

    GPI mobil: 48/100
    GPI dator: 96/100
    Total filstorlek: 4.1 MB

## Analys

### Stockholm stad
Det som sticker ut är den första inhämtningen där sidan laddades på 6 sekunder. Varför gick det så bra bara en gång? Många faktorer samspelar för att få sidan till klienten. Informationen som samlats in i denna undersökning är inte tillräcklig för att kunna avgöra hur sidan presterar. Uppenbarligen kan sidan inhämtas betydligt snabbare än vad genomsnittstiden vittnar om. Filstorleken på 2.7 MB är dessutom minst av alla i denna undersökning.

### Kiruna kommun
Kiruna kommuns hemsida laddar i snitt på 1 minut och 11 sekunder. Storleken är runt 10 gånger den av Stockholms och Trelleborgs sidor. Kollar man på vad som ryms i dessa 30 MB är det en sak som sticker ut bland resurserna. Bilder. En av bilderna är en .png på 5.1 MB. Kan den komprimeras utan att upplevelsen försämras? Förutom komprimering är det upp till kiruna kommun att fråga sig om inte vissa av dessa resurser kan tas bort, förminskas eller flyttas för att förbättra prestandan.

### Trelleborgs kommun
Sidan har bilder men dessa är runt 100 - 500 kb, på många ställen används ikoner istället för bilder. Storleken på sidan är liten i jämförelse med Kiruna men ändå runt 50% större än Stockholm. Trots det laddar sidan i snitt 15 gånger snabbare än Stockholm. Sannolikt finns en förklaring att hitta bland faktorer som inte ryms i denna undersökning.


