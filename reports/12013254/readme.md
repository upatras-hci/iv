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

<a href="https://github.com/polybar/polybar/releases"><img src="https://img.shields.io/github/release/polybar/polybar.svg"></a>
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

I decided to choose this course, because I would have the opportunity to expand my knowledge  and learn how the information is visualized correctly, which is part of my job. </br>


## Organization creation & webring
In this part of the lesson we the [Human - Computer Interaction 2022 - 2023 Organisation](https://github.com/upatras-HCI-2022), and the [webring of our team](https://upatras-hci-2022.github.io/webring/) , too.There is the [repository](https://github.com/upatras-HCI-2022/webring) of it.



## CV Site
At first,we wanted to create an online site that CV ,will to created automatically from a [yaml](https://learnxinyminutes.com/docs/yaml/.) file,  using Jekyll.  <br />
I create a branch 
* [link online CV](https://evangeliachatz.github.io/online-cv/) <br />
* [link CV repository](https://github.com/sharu725/online-cv) 

## Command Line -ArchLinux Installation
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



## Participatory content 1Α1
About this delivered, we decided all together that we will place content, regarding to how the art is highlighted.</be>
Text to Image AI is technology that converts text to Pictures/Images, using AI algorithms. The AI models are feed with a huge amount of pictures/images with a simple description
in order to be trained on converting text to images. These algorithms even if they can generate AI art, unreal images or funny paradox pictures,
there is a lot of lack of photorealism in most of the results. Of course there are huger and more clever text-to-image generator
but are not free to use.
The photo caption was created with the use of free Internet software "DeepAI", a Text To Image - AI Image Generator
and using "Dancing Animals" as input the input text.
</br>

![Dancing Animals](https://user-images.githubusercontent.com/99615706/216759149-247eda50-08ab-4aab-931f-2ee5b4ac69df.jpeg)</br>
<sup>The license terms of the photo can be found [here](https://raw.githubusercontent.com/CompVis/stable-diffusion/main/LICENSE)</sup>

* [gallery](https://github.com/EvangeliaChatz/_gallery-hci-2022/blob/master/text-to-image.md)
* [images](https://github.com/upatras-HCI-2022/images/commit/993d4264bf17d75fb7828c65365295907affe810) 
* [pull request](https://github.com/upatras-HCI-2022/site/pull/3/commits/10e1158ffa8c4013c05efaf20c64de13eef6fac) at organization's repository  </br>

<img width="1287" alt="image" src="https://user-images.githubusercontent.com/99615706/216762094-7cc6cc14-303e-43d1-95ac-546d51d15d64.png">[Riffusion](https://www.riffusion.com/) is a type of artificial neural network that generates music by utilizing images of sound instead of audio. It was created by Seth Forsgren and Hayk Martiros and is based on [Stable Diffusion](https://github.com/Stability-AI/stablediffusion), a pre-existing open-source model for generating images from text prompts. Riffusion takes these image files and converts them into audio files by running them through an inverse Fourier transform. Although the generated audio files are only a few seconds long, Riffusion has the ability to interpolate different files together by using the latent space between outputs and a functionality of Stable Diffusion known as img2img.
Riffusion has been described as "out of this world" music, but is unlikely to replace traditional music created by humans. The code for Riffusion was released on December 15, 2022 and is available on GitHub. It is one of several models derived from Stable Diffusion and falls within the subset of AI text-to-music generators. Other similar models include Mubert, which was released in December 2022 and used Stable Diffusion to turn descriptive text into music loops, and Google's MusicLM, which was published in January 2023. </br>

* [gallery](https://github.com/upatras-HCI-2022/_gallery/pull/23)
* [images pull request](https://github.com/upatras-HCI-2022/images/pull/18) 
* [pull request]() at organization's repository  </br>


## Participatory content 1Α2
For the participatory content 1A2 we added to the [slides](https://github.com/upatras-HCI-2022/site/tree/master/_slides) and [timeline](https://github.com/upatras-HCI-2022/site/tree/master/_timeline) folders from an [`art.md`](https://github.com/upatras-HCI-2022/site/blob/master/_slides/art.md) file which will gather all the images with their descriptions at organization's [repository](https://github.com/upatras-HCI-2022/site). </br> 
* [pull request for my additions](https://github.com/upatras-HCI-2022/site/pull/27)
</br>



## Custom Desktop Enviroment
For command line usage I installed a simple [window manager]( https://courses-ionio.github.io/help/cli/).
I also installed the following [packages](https://github.com/EvangeliaChatz/iv/blob/main/reports/commandLine_2_Solution):The Polybar font is package with default status bar.I tried the `hack` theme. Polybar package is for add to our desktop a status bar that shows information relative to CPU usage, RAM usage, information about connection, volume. The second package is a screensaver, fills it with moving images or patterns when the computer has been idle for a designated time.The third one, is the well known, VLC Player.
</br>
<sup>Sorry, for the videos that keep playing, just needed to show the full screen to show the custom enviroment elements</sup>

1.[Polybar](https://github.com/polybar/polybar) </br>
![Polybar](https://user-images.githubusercontent.com/99615706/216759556-31a9a9a8-518c-460c-89ab-255547a68533.png)
</br>


2.[Pipes](https://github.com/pipeseroni/pipes.sh)</br>
[![asciicast](https://asciinema.org/a/PrZft1RuUiJ1qmK9Q0C0scVBY.svg)](https://asciinema.org/a/PrZft1RuUiJ1qmK9Q0C0scVBY) </br>


3.[VLC Player](https://github.com/videolan/vlc) </br>
![VLC](https://user-images.githubusercontent.com/99615706/216759812-7581647e-4af4-4d51-a1ca-347be6439ebb.png)



## Participatory content 2Α
For this deliverable as a designer, I decided that the changes I will make to the exercises have to do with improving the UI so I chose the following interactive examples:</br>
-Sign up/Sign in form </br>
* [link pibook](https://wondrous-paletas-7dd991.netlify.app/remix/signupform/)
* [pull request](https://github.com/upatras-HCI-2022/site/pull/12)
 </br>
In this example I made changes such as changing the font sizes, as they were too large and spoiled the final result. </br>
Change in focus state, when the user clicks on a form field to fill it, and other minor changes seen in the code.</br>
-Animated tab bar
* [Pull request](https://github.com/upatras-HCI-2022/site/pull/18)
* [link pibook](https://wondrous-paletas-7dd991.netlify.app/remix/animated-tab-bar/)

## CV B
NA GRAPSW AUTO!!!

## Command line1 (iv cli)
In this exercise I used the [pastel](https://github.com/sharkdp/pastel) από τις [διαθέσιμες](https://github.com/epidrome/dokey) command from the available command line exercises.This package uses colors to enhance the CLI (Command Line Interface), that is, it prints colored texts to make them more beautiful and recognizable. I followed the repository instructions carefully.
Pastel is a command line tool for creating and editing colors in terminal applications. On Arch Linux, you can use Pastel to perform the following tasks: </br>
1.Generate color codes in various formats (e.g., RGB, HEX, ANSI). </br>
2.Apply color to text and background. </br>
3.Create color palettes. </br>
4.Change colors (e.g., lighten, darken, saturate). </br>
5.Display color information (e.g. RGB values, HEX codes, ANSI codes). </br>
6.These tasks can be performed with the various subcommands of the Pastel package. </br>
As a designer, I will use pastel package to generate color palletes. </br>

* First install the pastel package:
1. Install pastell package:
```sh
sudo pacman -S pastel
``` 

* For my work I use color code switching every day. For example, in this one I'm converting a #hex color to rgb:
2. Generate color codes in various formats:
```sh
pastel color c837ca | pastel format rgb
``` 

* The ability to find the complement of each color is also very useful:
3. Generate the complement color:
```sh
pastel color c837ca | pastel complement
```


* You can easily choose any color from the entire color spectrum:
4. Pick a color:
```sh
pastel pick
```


* Ι use color to improve the cli tools:
5. Print colorized text from a shell script, in order to make it more beautiful-usable:
```sh
pastel paint -n black --on red --bold "EXAMPLE"
```
</br>

The above commands are shown in the video below:
[![asciicast](https://asciinema.org/a/Jo6RRXTym6GYFDs1A3S39tEcz.svg)](https://asciinema.org/a/Jo6RRXTym6GYFDs1A3S39tEcz)

## Command line2 (iv cli)
icons-in-terminal-EDIT
NA GRAPSW!!!


## Participatory content 1B
Having dealt with software that converts text into image and music respectively, I decided to explore the field that converts speech into movements, and the wider field of voice recognition. </br>
In the first part (participatory 1B1), Voice Chess Challenger, developed in the 1970s, was one of the first examples of using voice interaction to play a game. The device used speech recognition technology to recognize voice commands and control the chessboard, allowing players to make moves by speaking into a microphone. This early application of speech recognition demonstrated the possibility of using voice commands to interact with electronic devices and helped lay the foundations for the development of modern speech recognition systems. It then takes a historical look back at the development of this industry, and examples of similar games are cited , based on voice recognition. </br>
* [link pibook](https://wondrous-paletas-7dd991.netlify.app/case-study/voice-chess-challenger/) </br>
* [link to the organization's repository](https://github.com/upatras-HCI-2022/site/blob/master/_case-study/voice-chess-challenger.md) </br>

In the second part, I looked into the same field and referred to the biography of one of the contributors to the history of voice recognition, Dudley Homer. Homer Dudley was an American electrical engineer and a pioneer in the field of speech recognition. Dudley is best known for his work to Vocoder1, an engine that analyzed and synthesized speech. Vocoder was one of the first speech recognition systems and helped lay the foundation for modern speech recognition technology. </br>
* [link pibook](https://wondrous-paletas-7dd991.netlify.app/biography/homer-dudley/) </br>
* [link to the organization's repository](https://github.com/upatras-HCI-2022/site/blob/master/_biography/homer-dudley.md) </br>


## CvB
Σε αυτό το παραδοτέο χρησιμοποίησα το [simple-cv](https://github.com/plain-plain-text/simple-cv) που αναφέρεται στην [εκφώνηση](https://courses-ionio.github.io/help/cv/) της άσκησης.Αφού εγκατέστησα το pandoc & το latex, έτρεξα το αρχείο process, για να μετατραπεί σε pdf. Τα παραπάνω βήματα φαίνονται στο asciinema που ακολουθεί.Επίσης για να ανανεώνω κάθε φορά τις αλλαγές έτρεχα την εντολή sh process.sh
[![asciicast](https://asciinema.org/a/AyARrivlbN1rfJdCAfLY0Ku0R.svg)](https://asciinema.org/a/AyARrivlbN1rfJdCAfLY0Ku0R) </br>


## Participatory content 2B





