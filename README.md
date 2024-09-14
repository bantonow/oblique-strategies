# oblique-strategies

Shell script to print a random card from Oblique Strategies by Brian Eno and Peter Schmidt.
====================

In order to add this script to your shell, you must put this directory in your ~/bin directory, and add the following line to your ~/.bashrc or ~/.zshrc file.

```
export PATH="$HOME/bin/oblique_strategies:$PATH"
```

Then, update your rc file with the following command:

```
source ~/.bashrc # if you're using bash
source ~/.zshrc # if you're using zshell
```

Finally, run this command to make the script executable

```
chmod +x ~/bin/oblique_strategies/oblique
```

Now, you can run the script in your shell by typing 

```
oblique
```

## Files of particular interest

[.always_forget.txt](.always_forget.txt) is an extensive cheat sheet of UNIX commands.

[.bashrc](.bashrc) contains my shell customizations.

## Install
```
git clone git@github.com:awdeorio/dotfiles.git
rsync -av dotfiles/ ~/
rm -rf dotfiles/
```