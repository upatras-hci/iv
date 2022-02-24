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
Επέλεξα το μάθημα Information Visualization, διότι πιστεύω πως θα με βοηθήσει να εξελίξω τις γνώσεις μου, να βελτιωθώ και να μάθω περισσότερα για τις δυνατότητες του GitHub.<br>

### CV-site
Σκοπός της άσκησης αυτής ήταν να δημιουργήσουμε το δικό μας βιογραφικό με χρήση του συστήματος Jekyll. Σε πρώτη φάση, έφτιαξα ένα brancnch με όνομα "gh-pages" και έπειτα δημιούργησα ένα φάκελο _data στον οποίο πρόσθεσα τα αρχεία yaml με τα προσωπικά μου στοιχεία. 'Υστερα κάλεσα τα αρχεία αυτά μέσω του config.yml και χρησιμοποίησα ένα Jekylls Theme μέσω του Github Pages για να οπτικοποιήσω το προσωπικό μου βιογραφικό. 

- **[ο σύνδεσμος του αποθετηρίου](https://github.com/ceid5452/cv/tree/gh-pages)** 
- **[ο σύνδεσμος στο site](https://ceid5452.github.io/cv/)** 

Σε δεύτερη φάση προσπάθησα να εγκαταστήσω στο τοπικό μου ένα Jekyll theme και να φτιάκω το βιογραφικό μου από την αρχή χωρίς την βοήθεια των Github Pages. Ύστερα ανέβασα το project απο το τοπικό μου στο Github. Η διαδικασία που ακολούθησα φαίνεται αναλυτικά στο αρχείο README.md στον παρακάτω σύνδεσμο.

- **[ο σύνδεσμος του αποθετηρίου](https://github.com/ceid5452/MyJekyllCV)** 
- **[ο σύνδεσμος στο site](https://myjekyllcv.netlify.app/)** 

### Content-2A
Προσθήκη 2 διαδραστικών παραδειγμάτων στο βιβλίο pibook:
 -  **[Link με τα commits](https://github.com/ceid5452/site/commits?author=ceid5452)**
 -  **[Burger Menu Slide Toggle](https://gallant-newton-f47024.netlify.app/remix/burger-menu/)**
 -  **[History tabs](https://gallant-newton-f47024.netlify.app/remix/tabs/)**

### CommandLine-1
Σε αυτή την άσκηση αρχικά προσπάθησα να εγκαταστήσω το ArchLinux σε Oracle VM VirtualBox, όμως δυστυχώς ο επεξεργαστής του συστήματος μου δεν το υποστήριζε, οπότε υλοποίησα την άσκηση αυτή στο τερματικό του macOS. Αρχικά λοιπόν αντικατέστησα το κλασσικό terminal εγκαθιστώντας το [iterm2](https://www.iterm2.com/) που είναι μια πιο συγχρονη έκδοση του terminal που λειτουργεί σε macOS και παρέχει πολλά features. Ύστερα έκανα install το [Homebrew](https://brew.sh/) ακολουθώντας τις οδηγίες του documentation. To Homebrew ουσιαστικά είναι ένα free open-source software package management system που απλοποιεί το installation του software στα Apple’s macOS. Πριν εγκαταστήσω το Homebrew, έπρεπε πρώτα να εγκαταστήσω τα εργαλεία CLI για το Xcode.

```
xcode-select —-install
```

Στη συνέχεια έκανα Install το ZSH εκτελώντας την εντολή:

```
brew install zsh
```

Και ακολουθώντας τις οδηγίες έκανα intall και το [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh). Το Oh My Zsh συνοδεύεται από πολλά θέματα. Το προεπιλεγμένο θέμα είναι robbyrussell, αλλά επέλεξα να το αλλάξω με το [agnoster](https://github.com/agnoster/agnoster-zsh-theme). Τέλος, έκανα install τα fonts για να αποκτήσω τις γραμματοσειρές [Powerline](https://github.com/powerline/fonts). Η παραπάνω διαδικασία φαίνεται αναλυτικά στον πρώτο σύνδεσμο:

 -  **[Asciinema](https://asciinema.org/) link for [Prowerline](https://asciinema.org/a/BPx0VB03jaQzdnsjfjemZF1ds)**

### MergeRequest-1
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Προσθήκη νέου στα posts: "Call for applications 2020-2021" ", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Έκανα checkout στον νέο branch που δημιούργησα "add_news". Στον φάκελο _news δημιούργησα ένα αρχείο .md με όνομα "2019-11-23-call_for_2020_2021.md" στο οποίο πρόσθεσα το περιεχόμενο του post που ήθελα να οπτικοποιήσω. Ύστερα, το περιεχόμενο του νέου post που δημιούργησα, οπτικοποιήθηκε στην σελίδα των posts. Έκανα commit και push τις αλλαγές μου και τέλος έκανα ένα merge request για να οπτικοποιηθούν και να συνεργαστούν οι προτεινόμενες αλλαγές μου στον πηγαίο κώδικα.</br>

- **[Issue](https://github.com/upatras-hci/site/issues/156)**
- **[Merge-request](https://github.com/upatras-hci/site/pull/158)**
- **[Site overview via netlify](https://add-news.netlify.app/news/)**

### CommandLine-2
Το [Neofetch](https://github.com/dylanaraps/neofetch) είναι ένα εργαλείο που μας επιτρέπει να λάβουμε βασικές πληροφορίες σχετικά με το εγκατεστημένο σύστημα. Είναι το ιδανικό εργαλείο για να μάθουμε με μια ματιά τα βασικά χαρακτηριστικά του λειτουργικού συστήματος που έχει εγκατασταθεί. 
Μπορούμε να το κάνουμε install πολύ απλά εκτελώντας την εντολή:

```
brew intall neofetch
```
Να επεξεργαστούμε το config file του:

```
sudo nano .config/neofetch/config.conf
```

Και να το ορίσουμε να εμφανίζεται κάθε φορά που ανοίγουμε το τερματικό προσθέτοντας απλά το λεκτικό "neofetch" μέσα στο .zshrc file
```
nano ~/.zshrc
```

```
neofetch
```

 -  **[Asciinema](https://asciinema.org/) link for [Neofetch](https://asciinema.org/a/jR3Awd51FwnDlKmAnvtoXKelx)**

### CV-pdf
Για την υλοποίηση της άσκησης αυτής αρχικά έκανα fork το simple-cv repo (από τα παραδείγματα που είχαν δοθεί σαν οδηγίες για την υλοποίηση της άσκησης (https://github.com/plain-plain-text/simple-cv)) και έπειτα έκανα git clone για να στήσω το project στο τοπικό μου ώστε να το επεξεργαστώ. Στη συνέχεια τροποποίησα τα files μέσα στα sections, metadata και τα προσάρμοσα στα δικά μου δεδομένα καθώς επίσης όρισα την σειρά εμφάνισης των δεδομένων μου από το αρχείο sections.txt. Έπειτα εγκατέστησα το pandoc και latex για να μπορώ να μετατρέψω τα αρχεία μου σε pdf. Τέλος έκανα git checkout στο branch που δημιούργησα "gh-pages" και έκανα push τις αλλαγές μου. 

Όσον αφορά την αυτόματη τοποθέτηση του pdf στην ιστοσελίδα του βιογραφικού με Continuous Integration κάθε φορά που υπάρχει αλλαγή στο αρχείο δεδομένων YAML, δοκίμασα να το υλοποιήσω μέσω του [Travis CI](https://travis-ci.org/) δημιουργώντας ένα αρχείο .travis.yml όπως φαίνεται [εδώ](https://github.com/ceid5452/simple-cv/blob/gh-pages/.travis.yml), όμως δεν μπόρεσα να κάνω build καθώς ήταν επι πληρωμή. Έτσι λοιπόν εφάρμοσα την τεχνολογία [Netlify CI](https://www.netlify.com/products/build/). Ακολουθούν οι σύνδεσμοι με όλες τις απαραίτητες πληροφορίες.

- **[Pdf link](https://ceid5452.github.io/simple-cv/docs/Filiopoulou_Dionysia_CV.pdf)** </br>
- **[Html link](https://ceid5452.github.io/simple-cv/docs/)**
- **[Netlify link](https://cv-simple.netlify.app/)**
- **[Netlify CI link](https://app.netlify.com/sites/cv-simple/deploys/62168da45f07f626cbeca0d9)**

**Deploy Log**
```
9:40:20 PM: Build ready to start
9:40:22 PM: build-image version: 122b31996ccaffd45d820a452d6227f8312110cc (focal)
9:40:22 PM: build-image tag: v4.5.3
9:40:22 PM: buildbot version: 4b36e839b4a8a6b4da7438120b4832cce296b644
9:40:22 PM: Fetching cached dependencies
9:40:22 PM: Failed to fetch cache, continuing with build
9:40:22 PM: Starting to prepare the repo for build
9:40:23 PM: No cached dependencies found. Cloning fresh repo
9:40:23 PM: git clone https://github.com/ceid5452/simple-cv
9:40:23 PM: Preparing Git Reference refs/heads/gh-pages
9:40:24 PM: Parsing package.json dependencies
9:40:24 PM: Different publish path detected, going to use the one specified in the Netlify configuration file: 'docs' versus '/' in the Netlify UI
9:40:25 PM: No build steps found, continuing to publishing
9:40:25 PM: Starting to deploy site from 'docs'
9:40:25 PM: Creating deploy tree 
9:40:25 PM: Creating deploy upload records
9:40:25 PM: 0 new files to upload
9:40:25 PM: 0 new functions to upload
9:40:25 PM: Starting post processing
9:40:25 PM: Post processing - HTML
9:40:25 PM: Post processing - header rules
9:40:25 PM: Post processing - redirect rules
9:40:25 PM: Post processing done
9:40:25 PM: Finished processing build request in 2.910478237s
9:40:26 PM: Site is live ✨
```

### CommandLine-3
To [fzf](https://github.com/junegunn/fzf) είναι ένα γενικής χρήσης **command-line** που μπορεί να χρησιμοποιηθεί σε οποιαδήποτε λίστα· files, command history, processes, hostnames, bookmarks, git commits, κ.λ.π. Για το installation το μόνο που χρειάζεται είναι να τρέξουμε τις εντολές:

```
brew install fzf

# To install useful key bindings and fuzzy completion:
$(brew --prefix)/opt/fzf/install
```

Έπαιτα press **control + R** και μπορείς να δεις τις εντολές που έχεις ήδη τρέξει.

 -  **[Asciinema](https://asciinema.org/) link for [fzf](https://asciinema.org/a/Kes6NLgrTVQgUdMSbOgU8tTen)**

### Content-2Β
Για την οπτικοποίηση του[βιβλίου](https://github.com/mibook/kallipos) αρχικά έκανα [fork] (https://github.com/ceid5452/kallipos) το αντίστοιχο repository, το κατέβασα τοπικά και ένα git checkout σε ένα δικό μου branch που δημιούργησα. Στη συνέχεια έκανα git clone τα submodules για να δημιουργήσω τα source files. Για την αρίθμηση των ψηφίων αλλά και των αναφορών των αρχείων κατά τη μετατροπή τους από markdown σε άλλες μορφές έκανα install το [pandoc-fignos](https://github.com/tomduck/pandoc-fignos). Έπειτα εφάρμοσα manual τα filters,με την εντολή που φαίνεται παρακάτω, για να φτιάξω το περιεχόμενο των κεφαλαίων, του πρόλογου και του επίλογου του βιβλίου.

```
pandoc --lua-filter=extras.lua text/ch01.txt --to markdown | pandoc --lua-filter=extras.lua --to markdown | pandoc --lua-filter=epigraph.lua --to markdown | pandoc --lua-filter=figure.lua --to markdown | pandoc --lua-filter=remove-notes.lua --to markdown | pandoc --metadata-file=meta.yml --citeproc --bibliography=bibliography/ch01.bib --reference-location=section --wrap=none --to markdown_strict > ch01.md
```

Αφού εφαρμόστηκαν τα φίλτρα σε όλα τα markdown files, τα έκανα concatenation σε ένα αρχείο με όνομα book.md

```
cat pre.md intro.md ch01.md ch02.md ch03.md ch04.md ch05.md ch06.md ch07.md ch08.md epi.md apx01.md > book.md
```

Τέλος μέσω του pandoc μετέτρεψα το book.md σε epub και δημιούργησα το βιβλίο μέσω της εντολής:

```
pandoc book.md -o epub.epub
```

- **[MIBOOK.epub](https://github.com/ceid5452/kallipos/commit/2bd6cb5c319c94d802babd4e991cc4f430eba3bb)** </br>
- **[EPUB](https://drive.google.com/drive/folders/1McOsUkr9kvKBgSADH3WGKaUxIBwP_Gf9?usp=sharing)** </br>

### CommandLine-4
**[autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)**

```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```
plugins=( 
    # other plugins...
    zsh-autosuggestions
)
```

 -  **[Asciinema](https://asciinema.org/) link for [autosuggestions](https://asciinema.org/a/nN8KmOepA6Q9Mq3gQmZ5GtSYd)**

### MergeRequest-2
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Available Master Thesis", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Εκεί, δημιούργησα ένα φάκελο _masterthesis και τοποθέτησα τα αρχεία .md με τα διαθέσιμα θέματα διπλωματικής. Ύστερα δημιούργησα τo file master-thesis.html στo οποία οπτικοποίησα το περιεχόμενο των αρχείων .md που δημιούργησα, ώστε να εμφανιστούν τα διαθέσιμα θέματα διπλωματικής.</br>

- **[Issue](https://github.com/upatras-hci/site/issues/155)**
- **[Merge-request](https://github.com/upatras-hci/site/pull/157)**
- **[Site overview via netlify](https://masterthesis.netlify.app/master-thesis/)**

### Final-Report
