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
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from /home/runner/opt/include/plumed_master/colvar/CoordinationBase.h:24,
from ./GHBFIX.sufoWR.cpp:22:
./GHBFIX.sufoWR.cpp: In constructor ‘PLMD::colvar::GHBFIX::GHBFIX(const PLMD::ActionOptions&)’:
./GHBFIX.sufoWR.cpp:139:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
139 |       plumed_assert(it<n)<<"itype ="<<it<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
./GHBFIX.sufoWR.cpp:140:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
140 |       plumed_assert(jt<n)<<"jtype ="<<jt<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : The GRID file you want to read: GRID, cannot be found!
[runnervmw9dnm:09135] *** Process received signal ***
[runnervmw9dnm:09135] Signal: Aborted (6)
[runnervmw9dnm:09135] Signal code:  (-6)
[runnervmw9dnm:09135] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd28cc45330]
[runnervmw9dnm:09135] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd28cc9eb2c]
[runnervmw9dnm:09135] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd28cc4527e]
[runnervmw9dnm:09135] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd28cc288ff]
[runnervmw9dnm:09135] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd28d0a5ff5]
[runnervmw9dnm:09135] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd28d0bb0da]
[runnervmw9dnm:09135] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd28d0a5a55]
[runnervmw9dnm:09135] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd28d0a5a6f]
[runnervmw9dnm:09135] [ 8] plumed_master(+0x146dd)[0x56087aa686dd]
[runnervmw9dnm:09135] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd28cc2a1ca]
[runnervmw9dnm:09135] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd28cc2a28b]
[runnervmw9dnm:09135] [11] plumed_master(+0x15365)[0x56087aa69365]
[runnervmw9dnm:09135] *** End of error message ***
</pre>
{% endraw %}
