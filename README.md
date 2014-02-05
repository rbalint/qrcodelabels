QR Code Labels
==============

QR Code Labels genarates QR codes of 3 UUID strings, 3 labels per each UUID on
one sheet ready to print. The UUID is also printed under each QR code in text.
The result looks something like this:

    +-+-+-+
    |1|1|1|
    +-+-+-+
    |2|2|2|
    +-+-+-+
    |3|3|3|
    +-+-+-+

QR Code Labels has originally been created for printing labels for moving boxes,
hence the 3 labels per each UUID.


Installation
------------

The scripts can be run from the top directory, no installation mechanism is provided.
To install the dependencies run:
`apt-get install texlive-extra-utils qrencode imagemagick inkscape`


Usage
-----

Just run `./qrlabelsgen`


License
-------

QR Code Labels has been released under the version 3 of the GNU General Public License, GPLv3.
Please see the included LICENSE file.


Contact
-------

Bug reports, feature suggestions, success reports, and patches/pull requests
are highly appreciated:

`https://github.com/rbalint/qrcodelabels`

`Balint Reczey <balint@balintreczey.hu>`