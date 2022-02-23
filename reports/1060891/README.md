## Personal Data:
Name: Vourna Maria-Melina <br /> 
ΑΜ: 1060891 

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
Ονομάζομαι Βουρνά Μαρία-Μελίνα και είμαι απόφοιτη του τμήματος Μαθηματικών του Παν.Πατρών. <br/>
Διαθέτω βασικές γνώσεις προγραμματισμού(Python,C++,Matlab). <br/>
Από το μάθημα  αυτό προσδοκώ να γνωρίσω καλύτερα το GitHub και τις δυνατότητές του ,καθώς είχα και έναν λογαριασμό παλιαότερα για πειραματισμό.

### CV-site
Σε αυτή την άσκηση χρησιμοποίησα ένα Jekylls Theme μέσω του Github Pages(jekyll-theme-hacker) για να φτιάξω το προσωπικό μου βιογραφικό. Αποθήκευσα τα δεδομένα μου σε ξεχωριστά αρχεία yaml για να μπορέσουν να παράξουν σε επόμενη εργασία το ιδιο βιογραφικό σε pdf μέσω Pandoc & Latex. 

- **[ο σύνδεσμος του αποθετηρίου](https://github.com/vournam/my_cv)** 

- **[ο σύνδεσμος στο site](https://vournam.github.io/my_cv/)** 

### Content-2A
Προσθήκη 2 διαδραστικών παραδειγμάτων στο βιβλίο pibook:
 -  **[ο σύνδεσμος με τα commits](https://github.com/vournam/site/commits/master)** 
 -  **[Button menu(pibook)](https://pibooksite1.netlify.app/remix/button-menu(pibook)/)**
 -  **[History of pc(sorting)](https://pibooksite1.netlify.app/remix/pc-history-sorting/)**

### CommandLine-1
Σε αυτή την άσκηση, αρχικά, εγκατέστησα το ArchLinux σε Oracle VM VirtualBox. Έπειτα, κατέβασα το [powerline](https://github.com/powerline/powerline) status bar στο command line του ArchLinux καθώς και το [neofetch](https://github.com/dylanaraps/neofetch), το οποίο όρισα να εμφανίζεται κάθε φορά που ανοίγω το τερματικό. (μέσω της προσθήκης "neofetch" στο startup file .bashrc) Κατέβασα και χρησιμοποίησα το dark [solarized](https://github.com/altercation/solarized) theme στο [tilix](https://gnunn1.github.io/tilix-web/) terminal emulator. 

- **[Asciinema](https://asciinema.org/) Links:**
*[PowerLine](https://asciinema.org/a/457054)*,
*[Neofetch](https://asciinema.org/a/457177)*,
*[Pywal](https://asciinema.org/a/457192)*

### MergeRequest-1
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Add_people", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Εκεί, πρόσθεσα ένα αρχείο .md μέσα στον φάκελο _people και μία εικόνα .png στον φάκελο assets/images. Έπτειτα, κατέβασα το Jekyll τοπικά ακολουθώντας τις [οδηγίες](https://jekyllrb.com/docs/installation/) της ιστοσελίδας Jekyll και στη συνέχεια μέσω της εντολής "bundle exec jekyll serve" έχοντας ήδη μπει μέσα στο φάκελο του HCI-site, εμφάνισα τοπικά την ανανεωμένη ιστοσελίδα του HCI-master site. Τέλος, έκανα μέσω τερματικού  ```git checkout -b add_people``` ώστε να δημιουργήσω ένα νέο branch και στην συνέχεια έκανα push στο συγκεκριμένο branch μέσω: ```git push --set-upstream origin add_people``` </br>

- **[Issue Link](https://github.com/upatras-hci/site/issues/153)**
- **[Merge-request Link](https://github.com/upatras-hci/site/pull/159/)** 
- **[Site Link](https://hci-site.netlify.app/people/)** 

### CommandLine-2
Στην άσκηση αυτή κατέβασα το [polybar](https://github.com/polybar/polybar), [rofi](https://github.com/davatorium/rofi), [awesome](https://github.com/awesomeWM/awesome), [pipes](https://github.com/pipeseroni/pipes.sh) και κατέβασα επιπλέον το [tilix](https://gnunn1.github.io/tilix-web/) μέσω της εντολής ```sudo pacman -S tilix``` και το [cava](https://github.com/karlstav/cava#configuration) audio visualizer. Τέλος, κατέβασα το [pastel](https://github.com/sharkdp/pastel) και έδωσα μία σειρά εντολών που συντέθηκαν μέσω "piping" του "output" μίας εντολής σε μία άλλη.

- **[Asciinema](https://asciinema.org/) Demo Links:**
*[Rofi](https://asciinema.org/a/457687)*,
*[Pipes](https://asciinema.org/a/458185)*,
*[Cava](https://asciinema.org/a/458152)*,
*[Pastel](https://asciinema.org/a/458180)*

### CV-pdf
Στην άσκηση αυτή έκανα αρχικά fork το [simple-cv](https://github.com/plain-plain-text/simple-cv) repo και έπειτα το κατέβασα τοπικά. Εκεί επεξεργάστηκα τα sections, metadata αλλά και όλα τα αρχεία του φακέλου templates ώστε να το προσαρμόσω στα δικά μου δεδομένα, είτε διαγράφοντας κάποια τμήματα(π.χ. twitter, telephone), είτε τροποποιώντας τα ήδη υπάρχοντα(π.χ. στα sections --> education, languages, skills). Στην συνέχεια, έφτιαξα ένα δικό μου branch "1060891" μέσω του terminal με την εντολή ```git checkout -b 1060891``` και στην συνέχεια μέσω τερματικού έδωσα τις εξής εντολές ώστε να ανέβει το ανανεωμένο repo στο 1060891 branch: </br>

```js
git add . 
git commit -m "Initial Commit"
git push --set-upstream origin 1060891
```
- **[ο σύνδεσμος του αποθετηρίου, Travic CI](https://github.com/vournam/simple-cv/tree/gh-pages)**  </br>
- **[Pdf & Html link](https://vourna-maria-melina-cv.netlify.app/)** </br>

Όσον αφορά την τεχνολογία [Travis CI](https://www.travis-ci.com/?utm_term=travis%20ci&utm_campaign=WW_en_Remarketing&utm_source=adwords&utm_medium=ppc&hsa_acc=4354966550&hsa_cam=10838935161&hsa_grp=108513102444&hsa_ad=573934944369&hsa_src=g&hsa_tgt=aud-931650538745%3Akwd-354950030127&hsa_kw=travis%20ci&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gclid=CjwKCAiAgbiQBhAHEiwAuQ6BkvyFbu5z7e99VsDTkuXx7yKWx7HIN5JkBqhKuvL-FELoH1VoYUTFvxoCGgsQAvD_BwE), έκανα fork το [repo](https://github.com/prewriter/LaTeX-Travis-Pages) και επεξεργάστηκα τα αρχεία .tex προσθέτοντας το δικό μου αρχείο .tex με τα στοιχεία του βιογραφικού μου. Το αρχείο .tex είχε δημιουργηθεί κατά την εκτέλεση του proccess.sh στο repo [simple-cv](https://github.com/vournam/simple-cv) στον φάκελο tmp/out.tex. Ωστόσο, δεν μπόρεσα να μπω στην ιστοσελίδα του Travis και να κάνω build καθώς ήταν επί πληρωμή.

- **[ο σύνδεσμος του αποθετηρίου](https://github.com/vournam/LaTeX-Travis-Pages/tree/gh-pages)**  </br>

'Ετσι λοιπόν, επέλεξα να εφαρμόσω την τεχνολογία [Netlify CI](https://www.netlify.com/products/build/): </br>
- **[Netlify build link](https://app.netlify.com/sites/vourna-maria-melina-cv/deploys/62167baa7cd7bc1078f1ce1d)**

### CommandLine-3
Σε αυτή την άσκηση, έχοντας ήδη κατεβάσει το [neofetch](https://github.com/dylanaraps/neofetch) θέλησα να προσθέσω μία εικόνα. Αρχικά, κατέβασα το w3m και το jp2a (αφορούν τον τρόπο απεικόνισης της εικόνας, περισσότερες πληροφορίες [εδώ](https://github.com/dylanaraps/neofetch/wiki/Image-Backends)), έλεγξα εάν υποστηρίζει εικόνες το terminal μου μέσω της εντολής ```w3m google.com```, το οποίο μου εμφάνισε κανονικά την ιστοσελίδα της Google. Έπειτα, μπήκα κι έκανα edit στο config file του neofetch που βρίσκεται στην τοποθεσία ```${HOME}/.config/neofetch/config.conf``` (Το config αρχικά υπήρχε στο /etc/neofetch/config.conf και με την εγκατάσταση έγινε copy αυτού μέσα στο ```${HOME}/.config/neofetch``` όπου υπάρχουν τα config files των εφαρμογών που χρησιμοποιεί ο κάθε χρήστης). Πιο συγκεκριμένα, στο #Image backend τμήμα του config file έκανα την αλλαγή στο image_backend από 'ascii' σε 'jp2a' την πρώτη φορά και σε 'w3m' την δεύτερη φορά και στο #Image Source έβαλα το path της εικόνας που ήθελα στο πεδίο image_source. Τέλος, έκανα reboot ώστε να εμφανιστεί η αλλαγή στο terminal.

- **[Asciinema](https://asciinema.org/) Link:**
*[Jp2a](https://asciinema.org/a/459412)*

```js
# Image backend.
#
# Default:  'ascii'
# Values:   'ascii', 'caca', 'catimg', 'jp2a', 'iterm2', 'off', 'tycat', 'w3m'
# Flag:     --backend
image_backend="jp2a

# Image Source
#
# Which image or ascii file to display.
#
# Default:  'auto'
# Values:   'auto', 'ascii', 'wallpaper', '/path/to/img', '/path/to/ascii', '/path/to/dir/'
# Flag:     --source
#
# NOTE: 'auto' will pick the best image source for whatever image backend is used.
#       In ascii mode, distro ascii art will be used and in an image mode, your
#       wallpaper will be used.
image_source="home/melina/Pictures/kitty.png"
```

### Content-2Β
Για την οπτικοποίηση του [βιβλίου](https://github.com/mibook/kallipos) σε ηλεκτρονικό βιβλίο (epub) αρχικά έκανα fork το αντίστοιχο repository και έπειτα το κατέβασα τοπικά μέσω της εντολής ```git submodule add $file``` για κάθε subdirectory μέσα στο directory kallipos. Στην συνέχεια, κατέβασα τοπικά μέσω της εντολής ```pip installl pandoc-fignos``` το pandoc fignos filter, του οποίου το executable το πρόσθεσα στο kallipos repository για να μπορέσω να το εφαρμόσω έπειτα ως φίλτρο. Ακόμη, δημιούργησα ένα αρχείο .sh, μέσω του οποίου θα μπορούσα να εφαρμόσω όλα τα φίλτρα με pipelining εκτελώντας το μέσω τερματικού. Αφού εκτέλεσα, λοιπόν, το .sh αρχείο, δημιουργήθηκε ένα αρχείο markdown, το οποίο μέσω της εντολής ```pandoc MIBOOK.md -o MIBOOK.epub``` μετατράπηκε στην συνέχεια σε ηλεκτρονικό βιβλίο.   </br>
- **[MIBOOK.epub](https://github.com/vournam/kallipos/blob/1060891/MIBOOK.epub)** </br>

### CommandLine-4
Στην άσκηση αυτή, κατέβασα το [pywal](https://github.com/dylanaraps/pywal) και μία εικόνα σύμφωνα με την χρωματική παλέτα της οποίας προσαρμόζεται το φόντο του terminal και πρόσθεσα κάποιες γραμμές κώδικα στο .bashrc ώστε η αλλαγή φόντου να ισχύει κάθε φορά που ανοίγω το τερματικό.

```js
# Import colorscheme from 'wal' asynchronously
# &   # Run the process in the background.
# ( ) # Hide shell job control messages.
# Not supported in the "fish" shell.
(cat ~/.cache/wal/sequences &)
<br/>
# Alternative (blocks terminal for 0-3ms)
cat ~/.cache/wal/sequences
<br/>
# To add support for TTYs this line can be optionally added.
source ~/.cache/wal/colors-tty.sh
```

- **[Asciinema](https://asciinema.org/) Link:**
*[Pywal](https://asciinema.org/a/457192)*

### MergeRequest-2
Σε αυτό το αίτημα ενσωμάτωσης αρχικά άνοιξα ένα issue με θέμα "Προσθήκη μαθημάτων, ερευνητικών ενδιαφερόντων και εκπαίδευσης σε κάθε καθηγητή", το οποίο αφού εγκρίθηκε ξεκίνησα να εργάζομαι γι'αυτό. Πιο συγκεκριμένα, έκανα πρώτα fork to [repository](https://github.com/upatras-hci/site) του hci-site και στην συνέχεια το έκανα clone τοπικά στον υπολογιστή μου. Εκεί, πρόσθεσα 6 αρχεία .html μέσα στον φάκελο _includes, 1 αρχείο .html στον φάκελο _layouts για το layout της σελίδας των καθηγητών, 1 αρχείο authors.yml στον φάκελο _data με τα δεδομένα κάθε καθηγητή όσον αφορά όνομα, email, ιστοσελίδα, εικόνα, τηλέφωνο, κ.λ.π. και επίσης πρόσθεσα στον φάκελο assets/images όσες εικόνες καθηγητών δεν υπήρχαν. Έπειτα, μέσω της εντολής ```bundle exec jekyll serve``` και έτσι, τρέχοντας την server address εμφάνισα τοπικά την ανανεωμένη ιστοσελίδα του HCI-master site. Τέλος, έκανα μέσω τερματικού  ```git checkout -b new_people ``` ώστε να δημιουργήσω ένα νέο branch και στην συνέχεια έκανα push στο συγκεκριμένο branch μέσω: ```git push --set-upstream origin new_people``` </br>

- **[Issue Link](https://github.com/upatras-hci/site/issues/161)**
- **[Merge-request Link](https://github.com/upatras-hci/site/pull/162)**
- **[Site Link](https://hci-site1.netlify.app/people/)** 

### Final-Report
