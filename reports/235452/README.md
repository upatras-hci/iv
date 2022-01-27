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
Σε αυτή την άσκηση χρησιμοποίησα ένα Jekylls Theme μέσω του Github Pages(jekyll-theme-hacker) για να φτιάξω το προσωπικό μου βιογραφικό. Αποθήκευσα τα δεδομένα μου σε ξεχωριστά αρχεία yaml για να μπορέσουν να παράξουν σε επόμενη εργασία το ιδιο βιογραφικό σε pdf μέσω Pandoc & Latex. 

- **[ο σύνδεσμος του αποθετηρίου](https://github.com/ceid5452/cv/tree/gh-pages)** 

- **[ο σύνδεσμος στο site](https://ceid5452.github.io/cv/)** 

### Content-2A
Προσθήκη 2 διαδραστικών παραδειγμάτων στο βιβλίο pibook:
 -  **[Burger Menu Slide Toggle](https://codepen.io/dFiliopoulou/pen/bGrajwM)**
 -  **[History tabs](https://codepen.io/dFiliopoulou/pen/mdMpLZN)**

### MergeRequest-1
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Add_people", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Εκεί, πρόσθεσα ένα αρχείο .md μέσα στον φάκελο _people και μία εικόνα .png στον φάκελο assets/images. Έπτειτα, κατέβασα το Jekyll τοπικά ακολουθώντας τις [οδηγίες](https://jekyllrb.com/docs/installation/) της ιστοσελίδας Jekyll και στη συνέχεια μέσω της εντολής "bundle exec jekyll serve" έχοντας ήδη μπει μέσα στο φάκελο του HCI-site, εμφάνισα τοπικά την ανανεωμένη ιστοσελίδα του HCI-master site. Τέλος, έκανα μέσω τερματικού  git checkout -b "add_people" ώστε να δημιουργήσω ένα νέο branch και στην συνέχεια έκανα push στο συγκεκριμένο branch μέσω: git push --set-upstream origin add_people. </br>

- **[Merge-request](https://github.com/upatras-hci/site/issues/155)**
- **[HCI-site]()**

### CV-pdf
Στην άσκηση αυτή έκανα αρχικά fork το [simple-cv](https://github.com/plain-plain-text/simple-cv) repo και έπειτα το κατέβασα τοπικά. Εκεί επεξεργάστηκα τα sections, metadata αλλά και όλα τα αρχεία του φακέλου templates ώστε να το προσαρμόσω στα δικά μου δεδομένα, είτε διαγράφοντας κάποια τμήματα(π.χ. twitter, telephone), είτε τροποποιώντας τα ήδη υπάρχοντα(π.χ. στα sections --> education, languages, skills). Στην συνέχεια, έφτιαξα ένα δικό μου branch "1060891" μέσω του terminal με την εντολή "git checkout -b 1060891" και στην συνέχεια μέσω τερματικού έδωσα τις εξής εντολές ώστε να ανέβει το ανανεωμένο repo στο 1060891 branch: </br>

- **[Pdf link]()** </br>
- **[Html link]()**
