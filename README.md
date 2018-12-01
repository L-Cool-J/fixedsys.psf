change linux console font
----------------------------
    cp fixedsys-116.psf /usr/share/kbd/consolefonts
    
    just test/One-time use:
    setfont fixedsys-116
    
    Permanent use:
    edit /etc/vconsole.conf fixedsys-116