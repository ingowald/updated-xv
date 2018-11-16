# LICENSE

This repository contains an updated version of John Bradley's original
'xv' program. Since John created it this way this program is
"SHAREWARE", free for non-commercial use, but not-free for
professional use. The original license can be found in original-docs/.

All changes made to xv are, from my point of view, free for anybody to
use. Basically, those changes consist of applyign all the pathces
required for newer versions of LINUX, plus buildign instructions, plus
whatever will come up during fixes and cleanups.

# PREREQUISITES

libtiff5-dev
libpng-dev

# BUILDING

To build, for now just do a 'make' in the root directory. I'll
probably go to cmake at some point in time, but for now I'll just need
it to build, so sticking with the original build scrips.

# CHANGES

- 11/2018 removed 'J2K' support - that library seems to no longer exist
- 11/2018 initial import, including all patches I could find.
