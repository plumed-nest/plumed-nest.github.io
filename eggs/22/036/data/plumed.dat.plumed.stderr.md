**Project ID:** [plumID:22.036]({{ '/' | absolute_url }}eggs/22/036/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/Keywords.h:29,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:27,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from /home/runner/opt/include/plumed/colvar/CoordinationBase.h:24,
from ./GHBFIX.u7ZdPe.cpp:22:
./GHBFIX.u7ZdPe.cpp: In constructor ‘PLMD::colvar::GHBFIX::GHBFIX(const PLMD::ActionOptions&)’:
./GHBFIX.u7ZdPe.cpp:139:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
139 |       plumed_assert(it<n)<<"itype ="<<it<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
./GHBFIX.u7ZdPe.cpp:140:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
140 |       plumed_assert(jt<n)<<"jtype ="<<jt<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : The GRID file you want to read: GRID, cannot be found!
[pkrvmbietmlfzoi:63663] *** Process received signal ***
[pkrvmbietmlfzoi:63663] Signal: Aborted (6)
[pkrvmbietmlfzoi:63663] Signal code:  (-6)
[pkrvmbietmlfzoi:63663] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2962045330]
[pkrvmbietmlfzoi:63663] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f296209eb2c]
[pkrvmbietmlfzoi:63663] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f296204527e]
[pkrvmbietmlfzoi:63663] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29620288ff]
[pkrvmbietmlfzoi:63663] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29624a5ff5]
[pkrvmbietmlfzoi:63663] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29624bb0da]
[pkrvmbietmlfzoi:63663] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29624a5a55]
[pkrvmbietmlfzoi:63663] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29624a5a6f]
[pkrvmbietmlfzoi:63663] [ 8] plumed(+0x146dd)[0x562c140c56dd]
[pkrvmbietmlfzoi:63663] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f296202a1ca]
[pkrvmbietmlfzoi:63663] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f296202a28b]
[pkrvmbietmlfzoi:63663] [11] plumed(+0x15365)[0x562c140c6365]
[pkrvmbietmlfzoi:63663] *** End of error message ***
</pre>
{% endraw %}
