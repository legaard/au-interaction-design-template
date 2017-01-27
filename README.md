# Interaktionsdesign skabelon
Dette projekt indeholder en simple skabelon til udvikling af prototyper i kurset
*Interaktionsdesign* (som udbydes på Aarhus Universitet).

For at kunne anvende "live reload" – dvs. browseren automatisk opdaterer siden når
ændringer forekommer – skal NodeJS installeres på maskinen der udvikles på. Du kan finde NodeJS [her](https://nodejs.org/en/).


## Indhold
I skabelonens `index.html` indlæses [jQuery](https://jquery.com/) og [Font Awesome](http://fontawesome.io/) (se head tag), hvilket gør det muligt at anvende disse bibliotkeker uden at foretage sig yderligere.

#### Font Awesome
Font Awesome er et CSS-bibliotek der tilbyder en række skalerbare vektor ikoner, som kan anvendes ved brug af et italics tag og *class* attributten. Et eksempel kunne være

```html
<i class="fa fa-umbrella"></i>
```
hvilket giver et paraply ikon.

Læs selv mere på deres [hjemmeside](http://fontawesome.io/).

#### jQuery
jQuery er et Javascript-bibliotek, som gør det nemt at arbejde med HTML DOM operationer, håndtering af events, animationer, etc. Et eksempel på jQuery kunne være

```javascript
$('#button').click(function(){
  console.log('Hello World!');
});
```

som printer 'Hello Word' i konsollen, hvert gang der bliver klikket på elementet med id'et *button*.

Læs selv mere på deres [hjemmeside](http://jquery.com/).

## Kom igang
Når NodeJS er installeret på maskinen, skal der navigeres (vha. Terminalen eller Windows Command Prompt) hen til folderen med skabelonen. Dernæst køres kommandoen

```
npm install
```

Herefter er `live-server` installeret lokalt i folderen. (`live-server` kan også installeres "globalt" ved at skrive `npm install -g live-server`. Gøres dette startes en server ved at skrive `live-server` i folderen). Nu kan serveren startes med kommandoen

```
npm start
```

Hver gang ændringer foretages og gemmes, vil browseren automatisk opdatere.

Det var alt – god fornøjelse!
