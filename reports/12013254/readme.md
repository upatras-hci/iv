# Οπτικοποίηση της Πληροφορίας

>> Μπορείτε να βρείτε τον πηγαίο κώδικα για τον παρακάτω πίνακα στο κουμπί `Raw` και μετά να τον αντιγράψετε στην αναφορά σας ως πίνακα περιεχομένων με σύνδεσμο προς τις υποενότητες-δραστηριότητες κάθε εβδομάδας.

| Εβδομάδα* | Παραδοτέο | Σύνδεσμος στην [εβδομαδιαία παρουσίαση προόδου στις συζητήσεις](https://github.com/upatras-hci/iv/discussions/categories/show-and-tell) | Αυτοαξιολόγηση σύμφωνα με τα κριτήρια της αντίστοιχης άσκησης |
| --- | --- | --- | --- |
| 1 | [Δημιουργία ομάδας](https://courses-ionio.github.io/help/team/) + [Φορκ και δημιουργία σελίδας τελικής αναφοράς](https://courses-ionio.github.io/help/guide/), [προσθήκη πίνακα περιεχομένων](https://raw.githubusercontent.com/upatras-hci/iv/master/README.md), [συγγραφή της εισαγωγής](https://courses-ionio.github.io/help/intro/), αποστολή της εισαγωγής [για σχολιασμό στην συζήτηση](https://github.com/upatras-hci/iv/discussions/categories/show-and-tell) και καταγραφή του συνδέσμου συζήτησης δίπλα --> |[CV introduction](https://github.com/upatras-hci/iv/discussions/35)| | 
| 2 | βιογραφικό Α | [CV A](https://evangeliachatz.github.io/online-cv/)  |
| 3 | γραμμή εντολών (arch linux) |[Arch Linux Virtual Box Installation](https://github.com/EvangeliaChatz/iv/blob/main/reports/commandLine_1_Solution)||
| 4 | συμμετοχικό 1A | [Participatory content 1Α](https://github.com/upatras-HCI-2022/site/pull/3/commits/10e1158ffa8c4013c05efaf20c64de13eef6facc)| |
| 5 | γραμμή εντολών (custom desktop environment) |[polybar](https://github.com/EvangeliaChatz/iv/blob/main/reports/Polybar_Installation.gif) [pipes](https://asciinema.org/a/PrZft1RuUiJ1qmK9Q0C0scVBY) [VLC Installation](https://github.com/EvangeliaChatz/iv/blob/main/reports/VLC_Installation.gif)| |
| 6 | συμμετοχικό περιεχόμενο 2Α | | |
| 7 | βιογραφικό Β | | |
| 8 | γραμμή εντολών (iv cli) | | |
| 9 | συμμετοχικό περιεχόμενο 1Β | | |
| 10 | γραμμή εντολών (iv cli) | | |
| 11 | συμμετοχικό περιεχόμενο 2Β | | |
| 12 | Τελική αναφορά* | | |


## Personal Information
Όνομα: Chatzilygeroudi Evangelia </br>
ΑΜ: 1018865

## Introduction
My name is Chatzilygeroudi Evangelia.
I used to work in finance , after my bachelor at [Department of Economics](https://www.econ.upatras.gr/el), but after many years of interaction with arts, jewelry(3D design) and make designs for friends and work, I discovered that design is my passion. </br>

I have been studying for six months, User Experience Design at [SAE Institute](https://www.sae.edu/grc/?) , so that I can make my designs beautiful and easy to use. At SAE Institute, I have had the chance to get to know the process (UX
Competitive Analysis, Neilsen Heuristics, User Interviews, Usability Testing,
Information Architecture, Navigation Design, Wireframes/Prototypes &
Design System) of User Centered Design, where I was introduced the
importance of analyzing the user’s behavior and use them at the design.
Now, I'm working at an Agency as UI/UX Designer.</br>

In addition, it’s in my plans to develop my skills in Front End programming
(HTML, CSS, Javascript).</br>

I decided to choose this course, because I would have the opportunity to expand my knowledge  and learn how the information is visualized correctly, which is part of my job.



## CV Site
At first,we wanted to create an online site that CV ,will to created automatically from a [yaml](https://learnxinyminutes.com/docs/yaml/.) file,  using Jekyll.  <br />
I create a branch 
* [link online CV](https://evangeliachatz.github.io/online-cv/) <br />
* [link CV repository](https://github.com/sharu725/online-cv) 


## Participatory content 1Α
About this delivered, we decided all together that we will place content, regarding to how the art is highlighted.</be>
Text to Image AI is technology that converts text to Pictures/Images, using AI algorithms. The AI models are feed with a huge amount of pictures/images with a simple description
in order to be trained on converting text to images. These algorithms even if they can generate AI art, unreal images or funny paradox pictures,
there is a lot of lack of photorealism in most of the results. Of course there are huger and more clever text-to-image generator
but are not free to use.
The photo caption was created with the use of free Internet software "DeepAI", a Text To Image - AI Image Generator
and using "Dancing Animals" as input the input text.
</br>


  ![Dancing Animals](https://github.com/EvangeliaChatz/iv/blob/main/text-to-image.jpeg) </br>
<sup>The license terms of the photo can be found [here](https://raw.githubusercontent.com/CompVis/stable-diffusion/main/LICENSE)</sup>


* [gallery](https://github.com/upatras-HCI-2022/_gallery/commit/03b3afcf79651c0230bbb28abcdbc3de3b2a2f68)
* [images](https://github.com/upatras-HCI-2022/images/commit/993d4264bf17d75fb7828c65365295907affe810)
* [pull request](https://github.com/upatras-HCI-2022/site/pull/3/commits/10e1158ffa8c4013c05efaf20c64de13eef6fac) at organization's repository  </br>

## Command Line 1-ArchLinux
Firsty, I tried to install Arch Linux with USB, but I couldn't input characters in terminale
So the installation was repeated in Virtual Box shown in the [photo](https://github.com/EvangeliaChatz/iv/blob/main/virtual%20box.png) below.So re-installed in Virtual Box </br> 
I followed the below steps: </br>

[---------------------Installation of powerline---------------------](https://github.com/powerline/powerline) </br>
1. Install powerline & powerline-fonts packages with sudo pacman:
```sh
sudo pacman -S powerline
``` 
2. Add the following lines to ~/.bashrc file in order to enable powerline:
```sh
vim .bashrc
``` 
3.Powerline-deamon -q #if this line creates error remove it

4.Finally, source .bashrc, or close and reopen Terminal
sudo pacman -S powerline powerline-font
```sh
sudo pacman -S powerline powerline-fonts
``` 
5.I Opened the .bashr file and erase the # to make them active

[![asciicast](https://asciinema.org/a/j9Q86Tlig0Is8ZLlA6InJVfQx.svg)](https://asciinema.org/a/j9Q86Tlig0Is8ZLlA6InJVfQx)



[---------------------Neofetch Installation---------------------](https://asciinema.org/a/YxVWdKOGY5LTYak37pSUJafmi) </br>
Neofetch is a tool that allows us to get basic information about the installed system. It is the ideal tool to learn at a glance the basic features of the installed operating system. We can install it very simply by running the command:</br>
1. Downolad neofetch package with:
```sh
sudo pacman -S neofetch
``` 
2. And run neofetch:
```sh
neofetch
``` 
[![asciicast](https://asciinema.org/a/YxVWdKOGY5LTYak37pSUJafmi.svg)](https://asciinema.org/a/YxVWdKOGY5LTYak37pSUJafmi)</br>



[--------------------- Solarized Installation---------------------](https://github.com/altercation/solarized) </br>
1. Download solarized package. There you will fine a file with name: solarized.vim:</br>
2. Move solarized.vim to ~/.vim/colors folder, if no exist create the folders using mkdir </br>
3. If you have no permissions to make that move, do it as a root </br>
4. To become root type: sudo -i </br>
5. Then create a vim file with name '.vimrc' on /home folder and place the below </br>
```sh
syntax enable set background=dark colorscheme solarized
``` 
6.From now the vim file will open with solarized theme.</br>
[![asciicast](https://asciinema.org/a/ed4oDeeBTOMuU5kxnJmNhgUZN.svg)](https://asciinema.org/a/ed4oDeeBTOMuU5kxnJmNhgUZN)


## Participatory content 2Α
For the participatory content 2A we added to the [slides](https://github.com/upatras-HCI-2022/site/tree/master/_slides) and [timeline](https://github.com/upatras-HCI-2022/site/tree/master/_timeline) folders from an `art.md` file which will gather all the images with their descriptions at organization's [repository](https://github.com/upatras-HCI-2022/site). At the moment there are some problems with the naming of the images as well as with the paths and for this reason the files are not properly connected to each other. It is expected to be fixed soon.

## Custom Desktop Enviroment
For command line usage I installed a simple [window manager]( https://courses-ionio.github.io/help/cli/).
I also installed the following [packages](https://github.com/EvangeliaChatz/iv/blob/main/reports/commandLine_2_Solution):The Polybar font is package with default status bar.I tried the `hack` theme. Polybar package is for add to our desktop a status bar that shows information relative to CPU usage, RAM usage, information about connection, volume. The second package is a screensaver, fills it with moving images or patterns when the computer has been idle for a designated time.The third one, is the well known, VLC Player.
</br>
<sup>Sorry, for the videos that keep playing, just needed to show the full screen to show the custom enviroment elements</sup>

1.[Polybar](https://github.com/adi1090x/polybar-themes)</br>
![polybar asciinema](https://github.com/EvangeliaChatz/iv/blob/main/reports/Polybar_Installation.gif)</br>


2.[Pipes](https://github.com/pipeseroni/pipes.sh)</br>
[![asciicast](https://asciinema.org/a/PrZft1RuUiJ1qmK9Q0C0scVBY.svg)](https://asciinema.org/a/PrZft1RuUiJ1qmK9Q0C0scVBY) </br>


3.VLC Player </br>
![VLC Player asciinema](https://raw.githubusercontent.com/EvangeliaChatz/iv/main/reports/VLC_Installation.gif)