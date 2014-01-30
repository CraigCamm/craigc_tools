Linux Commands
==============

Make command line tab autocomplete case insensitive

    if [ ! -a ~/.inputrc ]; then echo "\$include /etc/inputrc" > ~/.inputrc; fi
    echo "set completion-ignore-case On" >> ~/.inputrc
      
