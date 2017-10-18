# Worldspace

A webAR project to map and track physical world space for AR gaming uses.

This project is currently only usable on a mobile device that has googles tango hardware:

- Lenova Phab 2 pro
- Google Pixel
- Asus ZenPhone AR

Further more the webAR javascript API's are only currently implemented in a modified version of the Chomium browser.  See this [link](https://github.com/google-ar/WebARonTango) for further details.

The project (currently still in early phases of R&D) will map a users physical world using the tango sensors and remember this 'constructed world' allowing the developer to understand the users surroundings and place objects, characters, etc, in this world.  It will also provide API's for things like floor/wall detection and path-finding.

On a side note for various feasibility reasons, the project actually works by mapping 'empty space' rather than where solid surfaces are.  Therefore assuming that any unmapped area is solid.
