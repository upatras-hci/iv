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
My name is Filopoulou Dionysia and I have graduated from the Department of Computer Engineering and Informatics in 2017. <br>
The last three years I work as a frontend developer in a company which is located in Patras called eight8.<br>
I think this master will give me the opportunity to evolve and broaden my mind.<br>
Specifically the course "Information Visualization" will help me to learn best practices on github via projects.

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
Έκανα install την νεότερη έκδοση του jekyll και δημιούργησα μια νέα σελίδα με ένα default theme τοπικά στον υπολογιστή μου, ακολουθώντας τις [οδηγίες](https://jekyllrb.com/docs/installation/) της ιστοσελίδας Jekyll. Αποθήκευσα τα δεδομένα μου σε ξεχωριστά αρχεία yaml για να μπορέσουν να παράξουν το ιδιο βιογραφικό σε pdf μέσω Pandoc & Latex. 

- **[Pdf link](https://ceid5452.github.io/simple-cv/docs/Filiopoulou_Dionysia_CV.pdf)** </br>
- **[Html link](https://ceid5452.github.io/simple-cv/docs/)**

### MergeRequest-2
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Available Master Thesis", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Εκεί, δημιούργησα ένα φάκελο _masterthesis και τοποθέτησα τα αρχεία .md με τα διαθέσιμα θέματα διπλωματικής. Ύστερα δημιούργησα τo file master-thesis.html στo οποία οπτικοποίησα το περιεχόμενο των αρχείων .md που δημιούργησα, ώστε να εμφανιστούν τα διαθέσιμα θέματα διπλωματικής.</br>

- **[Issue](https://github.com/upatras-hci/site/issues/155)**
- **[Merge-request](https://github.com/upatras-hci/site/pull/157)**
- **[HCI-site]()**
