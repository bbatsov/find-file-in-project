Find file in project(FFIP)
==========

Overview
----------

FFIP makes it easy to find files in projects on which you're working on from
within Emacs. FFIP determines the root of the project automatically based on
the VCS(Version Control System) used in the project or the presence of 
"project files", such as .dir-locals.el, .emacs-project, etc.

Compatibility
----------

My setup is tested only on Emacs 23.2(currently the latest stable
Emacs version), so probably not everything will work on older Emacs
versions.

Installation
----------
Place the find-file-in-project.el somewhere on your Emacs load path.

`(add-to-list 'load-path "~/.emacs.d/find-file-in-project")`

Usage
----------

The find-file-in-project interactive function is where all the magic happens.
You're advised to bind it to some global key combination.

`(global-set-key (kbd "C-x C-M-f") 'find-file-in-project)`

Enjoy!

Bozhidar
