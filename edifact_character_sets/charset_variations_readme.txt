this directory contains some variations of edifact charsets.
in a regular installation good default charactersets are installed in usersys/charsets.
these defaults are the same as the unoa_regular and unob_regular.
if you want to use charactersets as provided in this download directory, copy the files you want to use to usersys/charsets, and rename to eg unoa.py
- unoa_regular  as in edifact standard, plus some extra characters that are often used in real live like <CR/LF>
- unob_regular  as in edifact standard, plus some extra characters that are often used in real live like <CR/LF>
- unoa_strict  as in edifact standard
- unob_strict  as in edifact standard
- unoa_like_unoc  UNOA is handled as if it is UNOC; so eg é and ö are OK
- unob_like_unoc  UNOA is handled as if it is UNOC; so eg é and ö are OK

'unoa_like_unoc.py' has all 256 values for characters. This might be easy as a starting point for extended character conversion.
