# IT-spillet
Repo for IT-spillet, et kortspil med samme regler som Cards Against Humanity og Det Dårlige Selskab, men med kort om IT-Produktudvikling. 

## Klargøring af spillet til print

Clone eller download repoet. 

Åben filen `cards.html` i din browser. 

Øverst på siden findet et input-felt til en fil. Tryk på `vælg fil` eller hvad der nu står, og vælg en fil, f.eks. `fyld.txt`. 

Hjemmesiden genererer nu et layout for hjemmesiden, hvor hver linje af input filen bliver placeret i et felt på hjemmesiden, klar til udskrift. 

Udskriv html siden: `Fil > Udskriv`, eller `Ctrl/CMD + P`

Indstil udskriften korrekt: 
1. Papirstørrelse skal være A4
2. Skalering skal være 100%, eller tilpas til bredden
3. Margener skal være sat til ingen, eller 0
4. Sidehoved og fod- skal ikke inkluderes. 

Vælg gem som PDF der hvor du vælger printer. 

Tryk gem (eller udskriv). 

For at klargøre et andet sæt, f.eks. sætningskort genindlæses siden og de foregående trin gentages. 

## Print af spillet

Spillet er designed til at blive printet på A4 papir. 

Det anbefales at benytte to forskellige farve papir; en til sætnings-kort, og en til fyld-kort. 

Almindeligt kopipapir er meget tyndt og gennemsigtigt nok til at teksten kan ses igennem. Benyt istedet karton, som kan findes i boghandlen. 

Brug en printer der kan udskrive på karton. Benyttes den i studiecaféen skal kartonen ligges i bypass skuffen på siden af maskinen, og denne skuffe skal vælges som papirkilde. 

Printes der fra en USB nøgle bør der ikke være problemer med at printeren tilføjer ekstra margen til siderne. 

Efter siderne er printet klippes eller skæres kortene ud. 

NOTE:
- Siderne kan evt lamineres for at gøre dem mere slidstærke, og mindre sårbare overfor væske. Hvorvidt det er bedst at laminerer og så skære, eller skære og så laminerer er ikke undersøgt endnu. 

- Det er muligt at farvet almindeligt papir der efterfølgende er lamineret er godt nok mht. gennemsigtighed of styrke. Det er heller ikke blevet undersøgt endnu. 

# Tilføjelser til spillet 

Alle er velkomne til at tilføje til spillet, eller bruge scriptet til andet formål. 

Hvis du har en masse gode idéer til nye kort må du gerne sende det til mig her, eller lave en pull request, så spillet forbedres for alle. 

## Begrænsninger 

### Orddeling 
`cards.html` bruger en ret primitiv metode til at dele ord, så et ord der er for langt til at kunne være på en linje bliver blot delt der hvor det ellers ville overflowe, uden nogen apostrof. 
F.eks. er ordet `studieprogrammør` netop ikke for langt, mens `virksomhedssamarbejde` er for langt, hvorfor de sidste to bogstaver kommer på en ny linje. 