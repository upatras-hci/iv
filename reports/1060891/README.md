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

[ο σύνδεσμος του αποθετηρίου](https://github.com/vournam/my_cv) 

[ο σύνδεσμος στο site](https://vournam.github.io/my_cv/) 

### Content-2A
Προσθήκη 2 διαδραστικών παραδειγμάτων στο βιβλίο pibook:
  1. [Button menu(pibook)](https://pibooksite1.netlify.app/remix/button-menu(pibook)/)
  2. [History of pc(sorting)](https://pibooksite1.netlify.app/remix/pc-history-sorting/)

### CommandLine-1
Σε αυτή την άσκηση, αρχικά, εγκατέστησα το ArchLinux σε Oracle VM VirtualBox. Έπειτα, κατέβασα το [powerline](https://github.com/powerline/powerline) status bar στο command line του ArchLinux καθώς και το [neofetch](https://github.com/dylanaraps/neofetch), το οποίο όρισα να εμφανίζεται κάθε φορά που ανοίγω το τερματικό. (μέσω της προσθήκης "neofetch" στο startup file .bashrc) Κατέβασα και χρησιμοποίησα το dark [solarized](https://github.com/altercation/solarized) theme στο [tilix](https://gnunn1.github.io/tilix-web/) terminal emulator. Τέλος, κατέβασα το [pywal](https://github.com/dylanaraps/pywal) και μία εικόνα σύμφωνα με την χρωματική παλέτα της οποίας προσαρμόζεται το φόντο του terminal και πρόσθεσα κάποιες γραμμές κώδικα στο .bashrc ώστε η αλλαγή φόντου να ισχύει κάθε φορά που ανοίγω το τερματικό.

/# Import colorscheme from 'wal' asynchronously </br>
/# &   # Run the process in the background. <br/>
/# ( ) # Hide shell job control messages. <br/>
/# Not supported in the "fish" shell. <br/>
/(cat ~/.cache/wal/sequences &) <br/>
/<br/>
/# Alternative (blocks terminal for 0-3ms) <br/>
/cat ~/.cache/wal/sequences <br/>
/<br/>
/# To add support for TTYs this line can be optionally added. <br/>
/source ~/.cache/wal/colors-tty.sh <br/>

[Asciinema](https://asciinema.org/) Links:
*[PowerLine](https://asciinema.org/a/457054)*,
*[Neofetch](https://asciinema.org/a/457177)*,
*[Solarized]()*,
*[Pywal](https://asciinema.org/a/457192)*

### MergeRequest-1

### CommandLine-2
Στην άσκηση αυτή κατέβασα το [polybar](https://github.com/polybar/polybar), [rofi](https://github.com/davatorium/rofi), [dunst](https://github.com/dunst-project/dunst), [awesome](https://github.com/awesomeWM/awesome), [pipes](https://github.com/pipeseroni/pipes.sh), [flashfocus](https://github.com/fennerm/flashfocus) και κατέβασα επιπλέον το [tilix](https://gnunn1.github.io/tilix-web/) μέσω της εντολής "sudo pacman -S tilix" και το [cava](https://github.com/karlstav/cava#configuration) audio visualizer. Τέλος, κατέβασα το [pastel](https://github.com/sharkdp/pastel) και έδωσα μία σειρά εντολών που συντέθηκαν μέσω "piping" του "output" μίας εντολής σε μία άλλη.

[Asciinema](https://asciinema.org/) Demo Links:
*[Rofi](https://asciinema.org/a/457687)*,
*[Dunst]()*,
*[Awesome]()*,
*[Pipes](https://asciinema.org/a/458185)*,
*[Flashfocus]()*,
*[Tilix]()*,
*[Cava](https://asciinema.org/a/458152)*,
*[Pastel](https://asciinema.org/a/458180)*

### CV-pdf

### CommandLine-3
Σε αυτή την άσκηση, έχοντας ήδη κατεβάσει το [neofetch](https://github.com/dylanaraps/neofetch) θέλησα να προσθέσω μία εικόνα. Αρχικά, κατέβασα το w3m και το jp2a (αφορούν τον τρόπο απεικόνισης της εικόνας, περισσότερες πληροφορίες [εδώ](https://github.com/dylanaraps/neofetch/wiki/Image-Backends)), έλεγξα εάν υποστηρίζει εικόνες το terminal μου μέσω της εντολής "w3m google.com", το οποίο μου εμφάνισε κανονικά την ιστοσελίδα της Google. Έπειτα, μπήκα κι έκανα edit στο config file του neofetch που βρίσκεται στην τοποθεσία ${HOME}/.config/neofetch/config.conf (Το config αρχικά υπήρχε στο /etc/neofetch/config.conf και με την εγκατάσταση έγινε copy αυτού μέσα στο ${HOME}/.config/neofetch όπου υπάρχουν τα config files των εφαρμογών που χρησιμοποιεί ο κάθε χρήστης). Πιο συγκεκριμένα, στο #Image backend τμήμα του config file έκανα την αλλαγή στο image_backend από 'ascii' σε 'jp2a' την πρώτη φορά και σε 'w3m' την δεύτερη φορά και στο #Image Source έβαλα το path της εικόνας που ήθελα στο πεδίο image_source. Τέλος, έκανα reboot ώστε να εμφανιστεί η αλλαγή στο terminal.

*[Jp2a](https://asciinema.org/a/459412)*

/# Image backend. <br/>
/# <br/>
/# Default:  'ascii' <br/>
/# Values:   'ascii', 'caca', 'catimg', 'jp2a', 'iterm2', 'off', 'tycat', 'w3m' <br/>
/# Flag:     --backend <br/>
**image_backend="jp2a"** <br/>

/# Image Source <br/>
/# <br/>
/# Which image or ascii file to display. <br/>
/# <br/>
/# Default:  'auto' <br/>
/# Values:   'auto', 'ascii', 'wallpaper', '/path/to/img', '/path/to/ascii', '/path/to/dir/' <br/>
/# Flag:     --source <br/>
/# <br/>
/# NOTE: 'auto' will pick the best image source for whatever image backend is used. <br/>
/#       In ascii mode, distro ascii art will be used and in an image mode, your <br/>
/#       wallpaper will be used. <br/>
**image_source="home/melina/Pictures/kitty.png"** <br/>

### Content-2Β

### CommandLine-4

### MergeRequest-2

### Final-Report
