**Project ID:** [plumID:22.036]({{ '/' | absolute_url }}eggs/22/036/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:29,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:27,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from /home/runner/opt/include/plumed_master/colvar/CoordinationBase.h:24,
from ./GHBFIX.pQFxjv.cpp:22:
./GHBFIX.pQFxjv.cpp: In constructor ‘PLMD::colvar::GHBFIX::GHBFIX(const PLMD::ActionOptions&)’:
./GHBFIX.pQFxjv.cpp:139:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
139 |       plumed_assert(it<n)<<"itype ="<<it<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:373:34: note: in definition of macro ‘plumed_assert’
373 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
./GHBFIX.pQFxjv.cpp:140:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
140 |       plumed_assert(jt<n)<<"jtype ="<<jt<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:373:34: note: in definition of macro ‘plumed_assert’
373 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: GHBFIX LABEL=group_1 PAIR GROUPA=20,18,494,492,1036,1034,1503,1505,1508,240,242,244,274,272,1252,1254,1257,1288,1286 GROUPB=1007,1005,1540,1538,2017,2015,523,525,527,779,781,784,1760,1758,1790,1792,1794,752,750 D_0=0.23 D_MAX=0.33 C=0.8 TYPES=typesTable.dat PARAMS=scalingParameters.dat
Maybe a missing space or a typo?
[fv-az1108-992:68718] *** Process received signal ***
[fv-az1108-992:68718] Signal: Aborted (6)
[fv-az1108-992:68718] Signal code:  (-6)
[fv-az1108-992:68718] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ffa58c42520]
[fv-az1108-992:68718] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ffa58c969fc]
[fv-az1108-992:68718] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ffa58c42476]
[fv-az1108-992:68718] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ffa58c287f3]
[fv-az1108-992:68718] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7ffa590a4f26]
[fv-az1108-992:68718] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7ffa590b6d9c]
[fv-az1108-992:68718] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7ffa590b6e07]
[fv-az1108-992:68718] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ffa590b70bb]
[fv-az1108-992:68718] [ 8] plumed_master(+0x12e7f)[0x558ac1d67e7f]
[fv-az1108-992:68718] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ffa58c29d90]
[fv-az1108-992:68718] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ffa58c29e40]
[fv-az1108-992:68718] [11] plumed_master(+0x13115)[0x558ac1d68115]
[fv-az1108-992:68718] *** End of error message ***
</pre>
{% endraw %}
