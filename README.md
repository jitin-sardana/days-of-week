# days-of-week

> This library provides the days of week in different languages like English, Spanish, Italian, Dutch, French, German, Hindi, Bengali, Marathi, Punjabi with abbreviations.

[![NPM](https://img.shields.io/npm/v/days-of-week.svg)](https://www.npmjs.com/package/days-of-week) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save days-of-week
```

## Usage

```jsx
ES6
import days from 'days-of-week'

ES5
const days = require('days-of-week');

Days in English
console.log(days.english); // ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]
console.log(days.abbr.english); // ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"]

Days in Spanish
console.log(days.spanish); // ["Domingo", "Lunes", "Martes", "Miércoles", "Jueves", "Viernes", "Sábado"]
console.log(days.abbr.spanish);// ["Dom", "Lun", "Mar", "Mié", "Jue", "Vie", "Sáb"]


Days in Italian
console.log(days.italian); // ["Domenica", "Lunedì", "Martedì", "Martedì", "Giovedì", "Venerdì", "Sabato"]
console.log(days.abbr.italian); // ["do.", "lun.", "mar.", "mer.", "gio.", "ven.", "sab."]


Days in Dutch
console.log(days.dutch); // ["zondag", "maandag", "dinsdag", "woensdag", "donderdag", "vrijdag",  "zaterdag"]
console.log(days.abbr.dutch); // ["zon", "ma", "di", "woe", "don", "vrij", "zat"]


Days in French
console.log(days.french); //  ["Dimanche", "Lundi", "Mardi", "Mercredi", "Jeudi", "Vendredi", "Samedi"]
console.log(days.abbr.french); //["Di", "Lu", "Ma", "Me", "Je", "Ve", "Sa"]


Days in German
console.log(days.german); // ["Sonntag", "Montag", "Dienstag", "Mittwoch", "Donnerstag", "Freitag", "Samstag"]
console.log(days.abbr.german); // ["So", "Mo", "Di", "Mi", "Do", "Fr", "Sa"]


Days in Hindi
console.log(days.hindi); // ["रविवार", "सोमवार", "मंगलवार", "बुधवार", "गुरूवार", "शुक्रवार", "शनिवार"]
console.log(days.abbr.hindi); // ["रवि", "सोम", "मंगल", "बुध", "गुरू", "शुक्र", "शनि"]


Days in Bengali
console.log(days.bengali) // ["রবিবার", "সোমবার", "মঙ্গলবার", "বুধবার", "বৃহস্পতিবার", "শুক্রবার", "শনিবার"]
console.log(days.abbr.bengali); // ["রবি", "সোম", "মঙ্গল", "বুধ", "বৃহস্পতি", "শুক্র", "শনি"]


Days in Punjabi
console.log(days.punjabi); // ["ਐਤਵਾਰ", "ਸੋਮਵਾਰ", "ਮੰਗਲਵਾਰ", "ਬੁੱਧਵਾਰ", "ਵੀਰਵਾਰ", "ਸ਼ੁੱਕਰਵਾਰ", "ਸ਼ਨੀਵਾਰ"]
console.log(days.abbr.punjabi); //["ਐਤ", "ਸੋਮ", "ਮੰਗਲ", "ਬੁੱਧ", "ਵੀਰ", "ਸ਼ੁੱਕਰ", "ਸ਼ਨੀ"]


Days in Marathi
console.log(days.marathi); // ["रविवार", "सोमवार", "मंगळवार", "बुधवार", "गुरूवार", "शुक्रवार", "शनिवार"]
console.log(days.abbr.marathi); // ["रवि", "सोम", "मंगळ", "बुध", "गुरू", "शुक्र", "शनि"]


```

## License

MIT © [jitin-sardana](https://github.com/jitin-sardana)
