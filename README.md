change linux console font
----------------------------
- Copy fixedsys-116.psf to /usr/share/kbd/consolefonts 

    `cp fixedsys-116.psf /usr/share/kbd/consolefonts`

- Just test/One-time use:

    `setfont fixedsys-116`

- Permanent use:

    `Set FONT=fixedsys-116 in /etc/vconsole.conf`

1