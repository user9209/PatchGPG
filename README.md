# GPG Patch

**PROFOUNDLY EXPERIMENTAL !!!**

Increases the maximum gpg key size to 64k keys

I can't figure out which affects this patch have on security !!!

**This is only for testing.**

Do not use it for productive gpg keys.


# To Use:
Download or checkout the gpg source code:

   git://git.gnupg.org/gnupg.git

apply the patches from folder

  paches

I used the commit
  685438bf6fe78c38919031a6ae35576ece7f47cf
from 04.04.2017 and run it on Ubuntu 16.04.2 64 bit. 

The message "gpg: Warning: using insecure memory!"
suggests that this is not a good idea to use this code.



# Related work:

David Norman created patches for gpg 1.4.12 and 2.0.18
but these did not work with the current version.
So I created this a new patch.
