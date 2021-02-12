## AM 7992

# παραδοτέα και τελική αναφορά

| παραδοτέο | εξωτερικος συνδεσμος |
| --- |--- |
| φορκ του αποθετηρίου και δημιουργία της σελίδας της αναφοράς με τα προσωπικά στοιχεία σας, της σύνοψης με αυτόν τον πίνακα περιεχομένων, και συγγραφή της εισαγωγής με περιγραφή των αναγκών και των στόχων σας για το αντίστοιχο μάθημα | [@moya10/iv/tree](https://github.com/moya10/iv/tree/7992)|
| ασκηση προγραμματισμού (pen-case)|  [form validation](https://codepen.io/moyadecka/pen/oNYbxYe) |
| ασκηση προγραμματισμού (pen-case)| [mouse eraser](https://codepen.io/moyadecka/pen/PobZzOq) |
| ασκηση προγραμματισμού (pen-case)| [draw with mouse](https://codepen.io/moyadecka/pen/MWaPovE) |
| ασκηση προγραμματισμού (pen-case)| [find my location](https://codepen.io/moyadecka/pen/WNxMrXE) |
| ασκηση προγραμματισμού (observablehq-notebook)| [edu-data-viz](https://observablehq.com/@moya10/edudata) |
| ασκηση γραμμής εντολών | [create aliases](https://github.com/moya10/dot) |
| ασκηση γραμμής εντολών | [neofetch setup]() |
| συμμετοχικό περιεχόμενο | [upatras-hci unofficial site](https://github.com/moya10/site) |
| τελική αναφορά | [@moya10/iv](https://moya10.github.io/iv) |

# Αναλυτικοτερα...

# ασκηση προγραμματισμου 1 - form validation

Δημιουργω μια [φορμα συμπληρωσης](https://codepen.io/moyadecka/pen/oNYbxYe) τηλεφωνου, ημεηλ και κωδικου. Tο τηλεφωνο θεωρειται εγκυρο αν περιεχει ενα prefix +XX και 10 αριθμους με βασει το regex `^([+]\d{2}[ ])?\d{10}$`

# ασκηση προγραμματισμου 2 - mouse easing-eraser

Χρησιμοποιησα τη βιβλιοθηκη [P5.js](https://p5js.org) για τη δημιουργια [κωδικα](https://codepen.io/moyadecka/pen/PobZzOq) που χρησιμοποιει την κινηση του ποντικιου για τον ελεχγο του μεγεθους ενος αντικειμενο και το σχεδιασμο μοτιβων. Οταν ο χρηστης "παταει το ποντικι" το αντικειμενο χανεται.

# ασκηση προγραμματισμου 3 - mouse draw
χρησιμοποιησα τη βιβλιοθηκη [P5.js](https://p5js.org) για τη δημιουργια διαδραστικου [κωδικα](https://codepen.io/moyadecka/pen/MWaPovE) που χρησιμοποιει την κινηση του ποντικιου για το σχεδιασμο μοτιβων.

# ασκηση προγραμματισμου 4 - find my location
χρησιμοποιησα το [google maps](https://codepen.io/moyadecka/pen/WNxMrXE) για να βρω την τοποθεσια μου στο χαρτη.

# οπτικοποιηση πληροφοριας με τη χρηση της βιβλιοθηκης d3.js

Δημιουγησα ενα [notebook](../observablehq/embed) στην σελιδα [observablehq](https://observablehq.com) για την απεικονιση δεδομενων που βρηκα στη σελιδα [UNdata](http://data.un.org/). Στο notebook, αρχικα παρουσιαζεται ο πινακας με τα δεδομενα συνολικα. Στη συνεχεια χρησιμοποιω γραφηματα barChart και pieChart που αναπαριστουν την κατανομη του πληθους των εγγραφων του γενικου πληθυσμου (αντρες, γυναικες) ανα εθνικοτητα σε τμηματα πρωτο/δευτερο/τριτο/βαθμιας εκπαιδευσης για τη χρονικη διαρκεια των ετων 2005-2019. Τα γραφηματα bubble χρησιμποιηθηκαν για περισσοτερη διαδραστικοτητα.

### πηγη

- [d3.js](https://alignedleft.com/tutorials)
- [vega-lite](https://vega.github.io/vega-lite/)
- [covid-19-bubble-chart-with-d3-render](https://observablehq.com/@unkleho/covid-19-bubble-chart-with-d3-render)
- [viz-ideas-for-us-chronic-disease-indicators-diabetes](https://observablehq.com/@clhenrick/viz-ideas-for-u-s-chronic-disease-indicators-diabetes)
- [pensylvania-elections](https://observablehq.com/@mariodelgadosr/pennsylvania-2020-general-election-mail-ballot-requests-a?collection=@mariodelgadosr/election-2020)

# ασκηση γραμμης εντολων 1 - some dots

Για τη διευκολυνση μου δημιουργησα στο αποθετηριο [dot](https://github.com/moya10/dot) καποια alias, γραμμες εντολων, για να επιταχυνω την εκτελεση εντολων

```alias ls='ls --color=always -rthla'```

η εντολη αυτη για παραδειγμα συνδυαζει ολες τις επιλογες -l, -a, -t, -h, και -r, με αποτελεσμα να μου παρεχει αυτοματα πληροφοριες για τα αρχεια ενος φακελου (κρυμμενα ή/οχι), το μεγεθος, τις αδειες και την ημερομηνια δημιουργιας τους τυπωνωντας τα σε μορφη λιστας.

# ασκηση γραμμης εντολων 2 - neofetch setup

Εγκατεστησα το πακετο neofetch ακολουθωντας τις οδηγιες στη σελιδα [wiki](https://github.com/dylanaraps/neofetch/wiki) του [αποθετηριου](https://github.com/dylanaraps/neofetch)

Στη συνεχεια επεξεργαστηκα μια φωτογραφια για να τη χρησιμοποιησω ως wallpaper.

Η επεξεργασια ξεκινησε μετατρεπoντας το αρχειο .png σε ascii .txt με τη χρηση του πακετου [Jp2a](https://github.com/cslarsen/jp2a). Αργοτερα προσθεσα ascii_colors, οπως φαινεται παρακατω.
| no_colors | colored |

<img src="https://moya10.github.io/iv/assets/images/moya.png" alt="codepen"  width="440" height="220" />  | <img src="https://moya10.github.io/iv/assets/images/moyaa.jpg" alt="codepen"  width="440" height="220" /> | 

# ασκηση γραμμης εντολων 3 - fetching torrents using  we-get

Επιλυση τεχνικων προβληματων στις ασκησεις γραμμης εντολων.

[επιλυση Issue](https://github.com/epidrome/dokey/issues/1)

# συμμετοχικο περιεχομενο -- συνεργατικη δημιουργια σελιδας του master

### προσωπικο αποθετηριο
*εισαγωγικα για τη δηιουργια της σελιδας χρησιμοποιουμε το θεμα [jekyll-minimal-mistakes](https://mmistakes.github.io/minimal-mistakes/)*

προσθηκη βιβλιογραφιας, οπου παρεχεται, για τα μαθηματα του μεταπτυχιακου, ακολουθωντας την τεκμηριωση του [jekyll-scolar](https://github.com/inukshuk/jekyll-scholar)

εχοντας ως αρχικο σκοπο τη δημιουργια βιβλιου για το site προχωρησα στη μετατροπη markdown --> pdf με τη χρηση pandoc, πχ 

```pandoc --from=markdown --template _layouts/intro.latex -o text/intro.pdf --pdf-engine=xelatex titlepage.md```

ολοκληρωση με [travis](https://travis-ci.com/moya10/site) [![Build Status](https://travis-ci.com/moya10/site.svg?branch=gh-pages)](https://travis-ci.com/moya10/site)

προσθηκη timeline, 👀 [Foundations of Interactive Computing](https://upatras-hci.netlify.app/posts/) 
    
για το timeline δημιουργω ενα αρχειο json, το οποιο περιεχει τα url που εκανα fetch απο την [playlist](https://www.youtube.com/channel/UCXRT71xdiJVlbgMpeMvUZ3g/playlists) και εχει την παρακατω δομη συμφωνα με τις οδηγιες του [TimelineJS repo](https://github.com/thecdil/timelinejs-template)

```js
{"events": 
    [{
        "start_date": {"year": "date"}, 
        "text": {"text": "some_text", "headline": "some_title"},
        "media": {"url": "some_url"}
    }]
}
```
* [προσωπικο αποθετηριο](https://github.com/moya10/site)  
* [οπτικοποιηση site στο προσωπικο αποθετηριο](https://upatras-hci.netlify.app)

### κεντρικο αποθετηριο

* [αιτημα ενσωματωσης στο κεντρικο αποθετηριο #1](https://github.com/upatras-hci/site/issues/140)
* [αιτημα ενσωματωσης στο κεντρικο αποθετηριο #2](https://github.com/upatras-hci/site/issues/141)
* [αιτημα ενσωματωσης στο κεντρικο αποθετηριο #3](https://github.com/upatras-hci/site/issues/142)
* [οπτικοποιηση site στο κεντρικο αποθετηριο](https://upatras-hci.github.io/site/)

# συμμετοχικο περιεχομενο -- προσθηκη υλικου στο βιβλιο [moya10/pibook](https://github.com/moya10/pibook) –> [epidrome/pibook](https://github.com/epidrome/pibook)

[the analytical engine](https://pibook10.netlify.app/gallery/analytical-engine/)  

Η Αναλυτική Μηχανή ήταν σχέδιο ενός μηχανικού υπολογιστή γενικής χρήσης από τον Βρετανό μαθηματικό Τσαρλς Μπάμπατζ, το οποίο αποτελεί σημαντικό βήμα στην ιστορία των υπολογιστών. Μπορούσε να προγραμματιστεί με τη χρήση διάτρητων καρτών. Δεν ήταν μία μοναδική φυσική μηχανή, αλλά μία ακολουθία από σχέδια που έφτιαχνε ο Μπάμπατζ μέχρι και το θάνατο του το 1871.

### πηγη 
[wiki](https://el.wikipedia.org/wiki/Αναλυτική_μηχανή)

# γιατι επελεξα αυτο το μαθημα
η διαδραση μου φανηκε διασκεδαστικη και ηθελα να κανω εξασκηση στον προγραμματισμο, το μαθημα συνδυαζει και τα δυο οποτε το επελεξα.

# γενικες εντυπωσεις
το εκπαιδευτικο υλικο που δοθηκε στα πλαισια του μαθηματος ηταν πληρες, το μαθημα ειχε σωστη κατευθυνση και αναγνωριζω οτι ο τροπος οργανωσης του ηταν καλος, θα το προτεινα και σε αλλους φοιτητες. 
