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
from ./GHBFIX.X5wvnF.cpp:22:
./GHBFIX.X5wvnF.cpp: In constructor ‘PLMD::colvar::GHBFIX::GHBFIX(const PLMD::ActionOptions&)’:
./GHBFIX.X5wvnF.cpp:139:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
139 |       plumed_assert(it<n)<<"itype ="<<it<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:373:34: note: in definition of macro ‘plumed_assert’
373 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
./GHBFIX.X5wvnF.cpp:140:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
140 |       plumed_assert(jt<n)<<"jtype ="<<jt<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:373:34: note: in definition of macro ‘plumed_assert’
373 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : The GRID file you want to read: GRID, cannot be found!
[fv-az768-943:05355] *** Process received signal ***
[fv-az768-943:05355] Signal: Aborted (6)
[fv-az768-943:05355] Signal code:  (-6)
[fv-az768-943:05355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6fd4842520]
[fv-az768-943:05355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6fd48969fc]
[fv-az768-943:05355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6fd4842476]
[fv-az768-943:05355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6fd48287f3]
[fv-az768-943:05355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6fd4ca2b9e]
[fv-az768-943:05355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6fd4cae20c]
[fv-az768-943:05355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6fd4cae277]
[fv-az768-943:05355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6fd4cae52b]
[fv-az768-943:05355] [ 8] plumed_master(+0x14274)[0x561c7d5db274]
[fv-az768-943:05355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6fd4829d90]
[fv-az768-943:05355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6fd4829e40]
[fv-az768-943:05355] [11] plumed_master(+0x14ed5)[0x561c7d5dbed5]
[fv-az768-943:05355] *** End of error message ***
</pre>
{% endraw %}
