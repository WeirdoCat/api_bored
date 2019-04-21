# api_bored
Dette er et lille project hvor jeg prøver at finde ud af hvordan jeg kan bruge JSON data.

Til dette bliver der brugt følgende ting

Handlebars:
I mit projekt er dette praktisk talt bare en måde jeg kan tage dataen der er i mit json, og herefter putte dette på siden. Dette bliver set når jeg finder "upvotes" eller "uploader" dette er nogle af de parametre som der kommer med mit data.

Materialize:
Dette er endnu en grund til at forkaste dig til fødderne af google, det eneste du skal gøre for at få en pæn hjemmeside er bare at give al din autonomi til dine altelskende capitalistiske herskere.

Derpibooru:
Dette er databasen som har alt JSON dataen og det er dem jeg kalder på for at få fat på mine billeder og mit data.

Der var især et specifikt sted i koden hvor jeg fik brug for hjælp, jeg havde et problem. Jeg ville gerne kunne sortere efter hvilke "tags" der skulle vises i mit kode. Jeg havde ingen anelse til hvordan jeg skulle gøre dette, men heldigvis var der en dejlig klassekamerat, navnligt Hampus, som der hjalp mig med dette. Han sagde at jeg skulle lave et "forloop", eller "foreachloop". 
Jeg lavede først en string som jeg puttede alle tags jeg ikke kunne lide ind i. Herefter skrev jeg således

banned.forEach(ban => {
              if (data.tags.includes(ban)) {
                shitsbanned = true;
              }
            });
            
Som man nok også kan se kom der en til variabel navnligt "shitsbanned" ind i koden, længere nede siger jeg så at hvis "shitsbanned" er sandt skal vi starte processen om igen. Dette syntes jeg var ekstremt sejt så shoutout til hampus og hans forloops.
