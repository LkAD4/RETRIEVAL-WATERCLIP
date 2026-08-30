Chat Better - server side
=========================

This folder belongs to whoever is HOSTING the world. On a dedicated
server that is the server owner; in singleplayer it is you.

server-config.json  Attachment limits and bandwidth settings. These are
                    enforced by the server, so clients cannot change or
                    bypass them. Edit and restart to apply.
history.json        Index of every attachment any player has sent: who,
                    when, what kind, how big, and where it was stored.
players/<name>/     The uploads themselves, one folder per player.

Archiving can be turned off in server-config.json (archiveUploads).
If you run a public server, tell your players that attachments are kept -
and check whether your local rules require you to say so.