rst-langspec
=============

Language specification for gnome applications (gtksourceview) including gedit3

Install
--------

   git clone git://github.com/hobsonlane/rst-langspec.git
   cd rst-langspec
   sudo cp rst.lang /usr/share/gtksourceview-2.0/language-specs/
   sudo cp rst.lang /usr/share/gtksourceview-3.0/language-specs/
   # sudo cp rst.lang ~/.local/share/gtksourceview-2.0/language-specs/
   # sudo cp rst.lang ~/.local/share/gtksourceview-3.0/language-specs/
   mkdir -p ~/.local/share/mime/packages
   cp x-rst.xml ~/.local/share/mime/packages/
   update-mime-database ~/.local/share/mime/

restart ``gedit``.

Uninstall
----------

   rm /usr/share/gtksourceview-2.0/language-specs/rst.lang
   rm /usr/share/gtksourceview-3.0/language-specs/rst.lang
   rm ~/.local/share/mime/packages/x-rst.xml
   update-mime-database ~/.local/share/mime/


