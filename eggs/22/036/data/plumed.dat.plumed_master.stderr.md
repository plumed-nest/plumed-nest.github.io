**Project ID:** [plumID:22.036]({{ '/' | absolute_url }}eggs/22/036/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:27,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from /home/runner/opt/include/plumed_master/colvar/CoordinationBase.h:24,
from ./GHBFIX.ing1wv.cpp:22:
./GHBFIX.ing1wv.cpp: In constructor ‘PLMD::colvar::GHBFIX::GHBFIX(const PLMD::ActionOptions&)’:
./GHBFIX.ing1wv.cpp:139:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
139 |       plumed_assert(it<n)<<"itype ="<<it<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
./GHBFIX.ing1wv.cpp:140:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
140 |       plumed_assert(jt<n)<<"jtype ="<<jt<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : The GRID file you want to read: GRID, cannot be found!
[fv-az1277-646:63745] *** Process received signal ***
[fv-az1277-646:63745] Signal: Aborted (6)
[fv-az1277-646:63745] Signal code:  (-6)
[fv-az1277-646:63745] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79e1245330]
[fv-az1277-646:63745] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79e129eb2c]
[fv-az1277-646:63745] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79e124527e]
[fv-az1277-646:63745] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79e12288ff]
[fv-az1277-646:63745] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79e16a5ff5]
[fv-az1277-646:63745] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79e16bb0da]
[fv-az1277-646:63745] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79e16a5a55]
[fv-az1277-646:63745] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79e16a5a6f]
[fv-az1277-646:63745] [ 8] plumed_master(+0x146dd)[0x5639e22ab6dd]
[fv-az1277-646:63745] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79e122a1ca]
[fv-az1277-646:63745] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79e122a28b]
[fv-az1277-646:63745] [11] plumed_master(+0x15365)[0x5639e22ac365]
[fv-az1277-646:63745] *** End of error message ***
</pre>
{% endraw %}
