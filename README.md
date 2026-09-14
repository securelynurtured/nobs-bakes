# Nobs Bakes


## Om Webbplatsen
Nobs Bakes är en enkel bageriwebbplats med fokus på tårtor, cupcakes och andra bakverk. Webbplatsen innehåller bland annat information om Nobs Bakes, favoritbakverk, blogg, kontaktuppgifter och ett kontaktformulär.

Syftet med projektet har varit att träna på att bygga upp en webbplats med tydlig HTML-struktur, använda bilder och länkar, arbeta med formulär och tabeller samt publicera webbplatsen online.



## Tekniker
I projektet har jag använt:

- HTML
- Git
- GitHub
- GitHub Pages
- Netlify

## Publicerade versioner
- Länk till Github Pages: https://securelynurtured.github.io/nobs-bakes/
- Länk till Netlify: https://nobs-bakes.netlify.app/

## Git-Frågår

### Vad är skillnaden mellan git add och git commit?
`git add` används för att välja vilka ändringar som ska tas med i nästa commit.  
`git commit` sparar sedan de valda ändringarna som en ny version i Git-historiken.

### Varför använder man branches istället för att jobba direkt i main?
Branches gör att man kan arbeta med ändringar separat utan att direkt påverka huvudversionen i `main`. När ändringen är klar kan den sedan testas och mergas tillbaka till `main`.

### Vad händer rent praktiskt när man gör en merge?
När man gör en merge slår Git ihop ändringarna från en branch med en annan branch. I mitt projekt gjorde jag en ändring i `dev`-branchen och mergade sedan tillbaka den till `main`.

### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
Att pusha till GitHub betyder att jag skickar mina commits och projektfiler från min dator till mitt GitHub-repository.

Att publicera på Netlify betyder att webbplatsen görs tillgänglig online som en fungerande webbsida med en publik webbadress.

### Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
Man skapar eller använder en `.gitignore`-fil och skriver namnet på den fil eller mapp som Git inte ska versionshantera.

Ett exempel i mitt projekt är `.DS_Store`, som är en dold macOS-fil som inte behöver sparas i Git.