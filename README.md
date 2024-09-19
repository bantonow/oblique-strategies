Oblique Strategies Card Puller 
====================

A shell script to print a random card from [Oblique Strategies](https://en.wikipedia.org/wiki/Oblique_Strategies) by Brian Eno and Peter Schmidt.

Ben Antonow | antonow@umich.edu | www.benantonow.com



This script requires Bash 4.0 or higher. I use the version of Bash that is in my /opt/homebrew/bin/bash to run this script, as Bash on MacOS is installed by default as Bash 3.2.57. I installed the most recent version of bash using homebrew, as I use MacOS. If you are a Mac user, you can ensure you have a correct version of bash installed by running: 

```
brew install bash
```

If you are a Windows user, or know you have Bash $\geq$ 4.0 installed elsewhere, you can modify the path in the shebang on line 1 of oblique.



In order to add this script to your shell, clone this repo in your ~/bin directory, and add the following line to your ~/.bashrc or ~/.zshrc file.

```
export PATH="$HOME/bin/oblique-strategies:$PATH"
```

Then, update your rc file with the following command:

If you're using bash:
```
source ~/.bashrc
```
If you're using zsh:
```
source ~/.zshrc
```

Finally, run this command to make the script executable

```
chmod +x ~/bin/oblique-strategies/oblique
```

Now, you can run the script in your shell by typing 

```
oblique
```

Credit:

* Created by Brian Eno and Peter Schmidt; first published in 1975. Buy a deck [here](https://www.enoshop.co.uk/product/oblique-strategies.html)

* _Eno_, 2024

* https://github.com/joelparkerhenderson/oblique-strategies

* https://monoskop.org/images/8/8c/Eno_Brian_Schmidt_Peter_Oblique_Strategies.pdf

* Eric Antonow, for buying me my own deck
