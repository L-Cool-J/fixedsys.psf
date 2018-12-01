change linux console font
----------------------------
    cp fixedsys-116.psf /usr/share/kbd/consolefonts
    
    Just test/One-time use:
    setfont fixedsys-116
    
    Permanent use:
    Change FONT=fixedsys-116 in /etc/vconsole.conf