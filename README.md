# LaboReeks Git
## **Labo 3**

In dit derde labo gaan we aan de slag met een .gitignore bestand en werken we met branches. We zullen ook hier de lokale wijzigingen gaan koppelen aan een remote git repository (GitHub). 

Je eindresultaat van het labo zal op deze manier automatisch in deze GitHub repository terecht komen. Met andere woorden, voor dit labo **upload je niks manueel** op GitHub! 
Alles wat gevraagd wordt dien je lokaal toe te voegen en vervolgens via de nodige commandos ook in de online repository te brengen.

#### **Aanvullende toets op Leho**
Na het afwerken van dit labo heb je op Leho een aanvullende toets met betrekking tot het labo en de leerstof gekoppeld aan het labo.
Je kan/mag de aanvullende toets steeds afleggen gebruik makend van alle bronnen (cursusmateriaal, labo, online bronnen, ...)

### **Labo 3:** *Takenlijst*
- [ ] Open de Git Bash Console op de locatie waar je dit labo wil gaan clonen. Dit kan via een rechtermuisklik op de locatie in kwestie en vervolgens de keuze **Git Bash Here** te selecteren.
>**Tip!** Indien deze optie niet beschikbaar is dan heb je een stap in de aanbevolen installatie in Labo 01 overgeslaan.

- [ ] Zorg ervoor dat de startsituatie *(deze repository)* van het labo op jouw pc **gecloned** wordt. Maak hiervoor gebruik van het passende git commando. 

- [ ]  Ga **na het clonen** via de console naar de gecloonde repository. Dit kan/mag je uiteraard ook doen door de nieuwe aangemaakt folder aan te klikken en hier opnieuw een Git Bash console te openen via de **Git Bash Here** optie.
>**Tip!** Controleer voor je verder werkte of je al dan niet in de juiste git repository zit! Je kan dit snel visueel vaststellen in je console.

- [ ] Voer even een extra controle uit om na te gaan welke remote repositories gekoppeld zijn na het clonen. Maak hiervoor gebruik van het passende git commando.

- [ ] Maak vervolgens een screenshot van de console commando's die je tot hiertoe gebruikt hebt en plaats deze in de **lokale** Screenshot folder die je in je labo3 folder staan hebt. *(Op jouw PC/laptop dus!)* Geef deze screenshot de naam **labo3_01** (met extensie naar keuze).

- [ ] Maak gebruik van passende git commando's om de nieuw(e) bestand(en) te commiten naar git.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

### Werken met **.gitignore**

- [ ] Maak een .gitignore bestand aan in de root van dit labo.

- [ ] zorg ervoor dat overheen de volledige git repository alle bestanden met extensie **tmp** niet opgenomen worden in git. Plaats de zin **temporary files are excluded** net boven de regel die je hiervoor gemaakt hebt, deze regel wordt als commentaar aanzien.

- [ ] Maak gebruik van passende git commando's om het .gitignore bestand te commiten naar git.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Voeg een regel toe aan de .gitignore die de folder **temp** zal gaan negeren. Plaats de zin **temporary folder is excluded** net boven de regel die je hiervoor gemaakt hebt, deze regel wordt als commentaar aanzien.
>**Tip!** Vergeet de wijzigingen niet op te slaan na je aanpassingen!

- [ ] Maak gebruik van passende git commando's om het .gitignore bestand te commiten naar git.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Bekijk de folder structuur van de **docs** folder even. Je zal zien dat deze 3 verschillende folders bevat, elk verwijzend naar een fase. 
Voeg als eerste volgende regel commentaar toe in je .gitignore **All phases except phase1 are ignored**.
Vervolgens voorzie je de nodige regels waardoor je alle bestanden in phase2 en phase3 zal negeren maar deze in phase1 niet!
Tracht dit te bekomen door efficient gebruik te maken van de .gitignore functionaliteit en niet door elke genegeerde phase folder op een afzonderlijke regel toe te voegen.
>**Tip!** Je zal hiervoor hoogstwaarschijnlijk 2 regels nodig hebben. Vergeet de wijzigingen niet op te slaan na je aanpassingen!

- [ ] Maak gebruik van passende git commando's om het .gitignore bestand te commiten naar git.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Kopieer onderstaande lijst van commando's *(in 1 keer)*. Plak deze vervolgens in je console. Na uitvoeren zal deze blijven staan op de **git status** regel. Voer deze uit en neem een screenshot van het resultaat. Deze screenshot plaats je in de **lokale** Screenshot folder die je in je labo3 folder staan hebt. *(Op jouw PC/laptop dus!)* Geef deze screenshot de naam **labo3_02** (met extensie naar keuze).

```
clear
touch file01.tmp
touch file02.temp
touch docs/file01.tmp
touch docs/file01.temp
touch docs/phase1/file01.md
touch docs/phase1/phase1.md
touch docs/phase1/phase2.md
touch docs/phase1/phase3.md
touch docs/phase2/file01.md
touch docs/phase2/phase1.md
touch docs/phase2/phase2.md
touch docs/phase2/phase3.md
touch docs/phase3/file01.md
touch docs/phase3/phase1.md
touch docs/phase3/phase2.md
touch docs/phase3/phase3.md
touch docs/phase1.md
touch docs/phase2.md
touch docs/phase3.md
clear
git status
```

- [ ] Maak gebruik van passende git commando's om alle lokale bestanden te commiten naar git. **Synchroniseer** vervolgens je lokale repository met de online repository op GitHub.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

### Aan de slag met **branches**

- [ ] Maak in je lokale repository een nieuwe branch aan. Deze nieuwe branch geef je je als naam **dev** mee. Ga vervolgens naar deze nieuwe aangemaakte branch. 
>**Tip!** Denk er aan voor je naar de volgende stap doorgaat om zeker te controleren dat je **niet** langer op de **master** branch aan het werk bent!

- [ ] zorg met een passend git commando dat je remote repository (GitHub) deze branch, alsook de inhoud ervan, ook binnenkrijgt en tevens linkt aan je lokale branch. 

- [ ] Vanuit je **dev branch** maak je vervolgens **2 nieuwe branches** aan. Deze branches geef je volgende namen:
    -  **portfolio-submarine-feature**
    -  **portfolio-locked-safe-feature**
>**Tip!** Zorg er zeker voor dat je je op de **dev** branch bevindt voor je aan de slag gaat met het aanmaken van nieuwe branches.

- [ ] switch een voor een naar deze nieuwe branches en zorg met een passend git commando dat je remote repository *(GitHub)* deze branches, alsook de inhoud ervan, ook binnenkrijgt en tevens linkt aan je lokale branches. 

- [ ] ga naar de **portfolio-locked-safe-feature** branch en ga vervolgens naar de src folder. Hierin vind je een index.html bestand waar we mee zullen werken. Open het index.html bestand in een editor naar keuze. 
>**Tip!** dubbelklik gerust even op dit html bestand om de huidige inhoud raad te plegen.

- [ ] Pas de index.html file aan door op **regel 103** onderstaande code te plakken.

```
<!-- Portfolio Item 5-->
    <div class="col-md-6 col-lg-4 mb-5 mb-md-0">
        <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal5">
            <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-center text-white"><i class="fas fa-plus fa-3x"></i></div>
            </div>
                <img class="img-fluid" src="assets/img/portfolio/safe.png" alt="" />
        </div>
    </div>
```

- [ ] Zorg ervoor dat de wijzigingen aan de index.html opgenomen worden in git. Synchroniseer hierna je lokale repository met je online repository.

- [ ] ga naar de **portfolio-submarine-feature** branch en ga terug naar het index.html bestand. Open het index.html bestand in een editor naar keuze. 
>**Tip!** dubbelklik gerust even op dit html bestand om de huidige inhoud raad te plegen.

- [ ] Pas de index.html file aan door op **regel 103** onderstaande code te plakken.

```
<!-- Portfolio Item 6-->
    <div class="col-md-6 col-lg-4">
        <div class="portfolio-item mx-auto" data-toggle="modal" data-target="#portfolioModal6">
            <div class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100">
                <div class="portfolio-item-caption-content text-center text-white"><i class="fas fa-plus fa-3x"></i></div>
            </div>
            <img class="img-fluid" src="assets/img/portfolio/submarine.png" alt="" />
        </div>
    </div>
```

- [ ] Zorg ook hier dat de wijzigingen aan de index.html opgenomen worden in git. Synchroniseer hierna je lokale repository met je online repository.

- [ ] ga naar de **dev** branch en voer onderstaande commandos uit.
```
clear
git remote
git branch
git log --oneline
```

- [ ] Neem een screenshot van het resultaat. Deze screenshot plaats je in de **lokale** Screenshot folder die je in je labo3 folder staan hebt. *(Op jouw PC/laptop dus!)* Geef deze screenshot de naam **labo3_03** (met extensie naar keuze).

- [ ] Maak gebruik van passende git commando's om alle lokale bestanden te commiten naar git. **Synchroniseer** vervolgens je lokale repository met de online repository op GitHub.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Merge vervolgens de wijzigingen die je in de **portfolio-locked-safe-feature** aangemaakt hebt met de **dev** branch.

- [ ] Merge vervolgens de wijzigingen die je in de **portfolio-submarine-feature** aangemaakt hebt met de **dev** branch.

- [ ] Zorg ervoor dat je de *conflicterende wijzigingen* oplost zodat **zowel de locked safe als de submarine** in de index.html blijven staan.

- [ ] Voer hierna onderstaande commandos uit.
```
clear
git branch
git log --oneline
```

- [ ] Neem een screenshot van het resultaat. Deze screenshot plaats je in de **lokale** Screenshot folder die je in je labo3 folder staan hebt. *(Op jouw PC/laptop dus!)* Geef deze screenshot de naam **labo3_04** (met extensie naar keuze).

- [ ] Maak gebruik van passende git commando's om alle lokale bestanden te commiten naar git. **Synchroniseer** vervolgens je lokale repository met de online repository op GitHub.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Na het voltooien van alle taken editeer je deze readme.md file. **LET OP!** dit doe je deze keer in je lokale readme.md file! Plaats alle tasks op voltooid door de markup te wijzigen van [ ] naar [x].
>**Tip!** Je zit hier nog steeds op de **dev** branch. Je kan hier gerust VS Code gaan gebruiken. Deze heeft ook een preview mode om met markdown aan de slag te gaan.

- [ ] Maak gebruik van git commando's om vervolgens deze wijzigingen ook aan je lokale git repository toe te voegen. Zorg bij je **commit** voor een passende **commit message**.
>**Tip!** Indien je twijfelt aan de syntax raadpleeg dan je cursus.

- [ ] ga naar de **master** branch en zorg ervoor dat deze branch geupdate wordt met de huidige status van de **dev** branch.

- [ ] Zorg ervoor dat je lokale repository nu ook nog een laatste keer gesynchroniseerd wordt naar deze GitHub repository toe.
