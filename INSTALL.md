It is assumed that you have already enabled one or more of the Swedish locales.

To install this replacement locale, find the locale definition files on your system (Ubuntu places them in `/usr/share/i18n/locales`, for example) and replace the file `sv_SE` with the file from this repository.
I strongly suggest you make a backup before doing so. You can then run the `locale-gen` command to rebuild your locale database.
