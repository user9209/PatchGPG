# GPG Patch

**PROFOUNDLY EXPERIMENTAL !!!**

Increases the maximum gpg key size to 64k keys.

I can't figure out which affects this patch have on security !!!

**This is only for testing.**

Do not use it for productive gpg keys.


# To Use:
Download or checkout the gpg source code:

   *git://git.gnupg.org/gnupg.git*

apply the patch from folder:

  *paches*

I used the commit
  *943176c73208f1484de8b0c34b2ad1d189e88495*
from 03.04.2017 and run it on Ubuntu 16.04.2 64 bit.

**I never generated a key greater than 16k as this takes ~10 minutes.**

The message "gpg: Warning: using insecure memory!"
supposes that this is not a good idea to use this code.



# Related work:

David Norman created patches for gpg 1.4.12 and 2.0.18 but these patches did not work with the current version.

So I created this new patch.
