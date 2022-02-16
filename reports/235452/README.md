## Personal Data:
Name: Filiopoulou Dionysia <br /> 
ΑΜ: 2354542

<b>#Information Visualization:</b><br>
Δημιουργία Αναφοράς (README.md) και υποβολή παραδοτέου<br>

## Information Visualization:
| Εβδομάδα* | Παραδοτέο |
| --- | --- |
| 1 | [Εισαγωγή](#Introduction) |
| 2 | [Βιογραφικό-site](#CV-site) |
| 3 | [Συμμετοχικό περιεχόμενο 2A](#Content-2A) |
| 4 | [Γραμμή εντολών 1](#CommandLine-1)
| 5 | [Αίτημα ενσωμάτωσης 1](#MergeRequest-1) |
| 6 | [Γραμμή εντολών 2](#CommandLine-2) |
| 7 | [Βιογραφικό-pdf](#CV-pdf) |
| 8 | [Γραμμή εντολών 3](#CommandLine-3) |
| 9 | [Συμμετοχικό περιεχόμενο 2B](#Content-2Β) |
| 10 | [Γραμμή εντολών 4](#CommandLine-4)|
| 11 | [Αίτημα ενσωμάτωσης 2](#MergeRequest-2) |
| 12 | [Τελική αναφορά](#Final-Report) |

### Introduction:
Ονομάζομαι Φιλιοπούλου Διονυσία και είμαι απόφοιτη του τμήματος Μηχανικών Η/Υ και Πληροφορικής Πανεπιστημίου Πατρών. Αποφοίτησα από το τμήμα τον Δεκέμβριο του 2017 και τα τελευταία 3 χρόνια εργάζομαι σαν Frontend Developer.<br>

### CV-site
Σκοπός της άσκησης αυτής ήταν να δημιουργήσουμε το δικό μας βιογραφικό με χρήση του συστήματος Jekyll. Σε πρώτη φάση, έφτιαξα ένα brancnch με όνομα "gh-pages"και έπειτα δημιούργησα ένα φάκελο _data στον οποίο πρόσθεσα τα αρχεία yaml με τα προσωπικά μου στοιχεία. 'Υστερα κάλεσα τα αρχεία αυτά μέσω του config.yml και χρησιμοποίησα ένα Jekylls Theme μέσω του Github Pages για να φτιάξω το προσωπικό μου βιογραφικό. 

- **[ο σύνδεσμος του αποθετηρίου](https://github.com/ceid5452/cv/tree/gh-pages)** 
- **[ο σύνδεσμος στο site](https://ceid5452.github.io/cv/)** 

### Content-2A
Προσθήκη 2 διαδραστικών παραδειγμάτων στο βιβλίο pibook:
 -  **[Link με τα commits](https://github.com/ceid5452/site/commits?author=ceid5452)**
 -  **[Burger Menu Slide Toggle](https://gallant-newton-f47024.netlify.app/remix/burger-menu/)**
 -  **[History tabs](https://gallant-newton-f47024.netlify.app/remix/tabs/)**

### MergeRequest-1
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Προσθήκη νέου στα posts: "Call for applications 2020-2021" ", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Έκανα checkout στον νέο branch που δημιούργησα "add_news". Στον φάκελο _news δημιούργησα ένα αρχείο .md με όνομα "2019-11-23-call_for_2020_2021.md" στο οποίο πρόσθεσα το περιεχόμενο του post που ήθελα να οπτικοποιήσω. Ύστερα, το περιεχόμενο του νέου post που δημιούργησα, οπτικοποιήθηκε στην σελίδα των posts. Έκανα commit και push τις αλλαγές μου και τέλος έκανα ένα merge request για να οπτικοποιηθούν και να συνεργαστούν οι προτεινόμενες αλλαγές μου στον πηγαίο κώδικα.</br>

- **[Issue](https://github.com/upatras-hci/site/issues/156)**
- **[Merge-request]()**
- **[HCI-site]()**

### CV-pdf
Για την υλοποίηση της άσκησης αυτής αρχικά έκανα fork το simple-cv repo (από τα παραδείγματα που είχαν δοθεί σαν οδηγίες για την υλοποίηση της άσκησης (https://github.com/plain-plain-text/simple-cv)) και έπειτα έκανα git clone για να στήσω το project στο τοπικό μου ώστε να το επεξεργαστώ. Στη συνέχεια τροποποίησα τα files μέσα στα sections, metadata και τα προσάρμοσα στα δικά μου δεδομένα καθώς επίσης όρισα την σειρά εμφάνισης των δεδομένων μου από το αρχείο sections.txt. Έπειτα εγκατέστησα το pandoc και latex για να μπορώ να μετατρέψω τα αρχεία μου σε pdf. Τέλος έκανα git checkout στο branch που δημιούργησα "gh-pages" και έκανα push τις αλλαγές μου.

- **[Pdf link](https://ceid5452.github.io/simple-cv/docs/Filiopoulou_Dionysia_CV.pdf)** </br>
- **[Html link](https://ceid5452.github.io/simple-cv/docs/)**

### Content-2Β
Για την οπτικοποίηση του[βιβλίου](https://github.com/mibook/kallipos) αρχικά έκανα [fork] (https://github.com/ceid5452/kallipos) το αντίστοιχο repository, το κατέβασα τοπικά και ένα git checkout σε ένα δικό μου branch που δημιούργησα. Στη συνέχεια έκανα git clone τα submodules για να δημιουργήσω τα source files. Για την αρίθμηση των ψηφίων αλλά και των αναφορών των αρχείων κατά τη μετατροπή τους από markdown σε άλλες μορφές έκανα install το [pandoc-fignos](https://github.com/tomduck/pandoc-fignos).

- **[MIBOOK.epub](https://github.com/ceid5452/kallipos/commit/2bd6cb5c319c94d802babd4e991cc4f430eba3bb)** </br>


### MergeRequest-2
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Available Master Thesis", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Εκεί, δημιούργησα ένα φάκελο _masterthesis και τοποθέτησα τα αρχεία .md με τα διαθέσιμα θέματα διπλωματικής. Ύστερα δημιούργησα τo file master-thesis.html στo οποία οπτικοποίησα το περιεχόμενο των αρχείων .md που δημιούργησα, ώστε να εμφανιστούν τα διαθέσιμα θέματα διπλωματικής.</br>

- **[Issue](https://github.com/upatras-hci/site/issues/155)**
- **[Merge-request](https://github.com/upatras-hci/site/pull/157)**
- **[HCI-site]()**
