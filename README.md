# Laravel 5 Snippets for Sublime Text

This fork updates blade syntax and adds a few other useful things.

### Installation
**With the Package Control plugin** :
The easiest way to install **Laravel 5 Snippets** is through Package Control, which can be found at [http://wbond.net/sublime_packages/package_control](http://wbond.net/sublime_packages/package_control).

```
Using Package Manager, search for "Laravel 5 Snippets"
```

**Without Git** :
Download the latest source from GitHub and copy the "Laravel 5 Sippets" folder to your Sublime Text "Packages" directory.

**With Git** :
Clone the repository in your Sublime Text "Packages" directory:

```
git clone https://github.com/rzb/laravel-5-snippets.git "Laravel 5 Snippets"

```
A default configuration in ST3 threats '@' as a "character that is considered to separate words". This prevents the blade snippets from triggering until you type the whole tabTrigger parameter. To fix this, just add this line to your user preferences:

"word_separators": "./\()\"'-:,.;<>~!#$%^&*|+=[]{}`~?"