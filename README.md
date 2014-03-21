krapps_remote
=============

MIDI remote to drive several computers with one device (keyboard or midi controller).
The patch repeat the received MIDI commands to all MIDI out devices.
It also maps keyboard input to MIDI note.

`krapps_remote` is a `init.d` script and should be placed/linked to `/etc/init.d`
Then to load it at startup run :
`$ sudo update-rc.d krapps_remote defaults`

To start manually with gui :
`$ sudo service krapps_remote start gui`

To stop the running patch : 
`$ sudo service krapps_remote stop`

And to start without gui : 
`$ sudo service krapps_remote stop`
