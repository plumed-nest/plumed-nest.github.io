**Project ID:** [plumID:22.036]({{ '/' | absolute_url }}eggs/22/036/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed_master/colvar/Colvar.h:24,
from /home/runner/opt/include/plumed_master/colvar/CoordinationBase.h:24,
from ./GHBFIX.OsVSfP.cpp:22:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from /home/runner/opt/include/plumed_master/colvar/../core/ActionAtomistic.h:27:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:94: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
94 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:100: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
100 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:102: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
102 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:108: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
108 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:112: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
112 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:116: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
116 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:120: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
120 | #pragma acc routine seq
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Pbc.h:123: warning: ignoring ‘#pragma acc routine’ [-Wunknown-pragmas]
123 | #pragma acc routine seq
|
In file included from /home/runner/opt/include/plumed_master/colvar/../core/Colvar.h:27:
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Matrix.h:100: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
100 | #pragma acc enter data copyin(this[0:1],sz,data[0:sz])
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Matrix.h:103: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
103 | #pragma acc exit data delete(data[0:sz],sz,this[0:1])
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Matrix.h:117: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
117 | #pragma acc enter data copyin(this[0:1])
|
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Matrix.h:123: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
123 | #pragma acc exit data delete( this[0:1])
|
In file included from /home/runner/opt/include/plumed_master/colvar/../core/../tools/Keywords.h:30,
from /home/runner/opt/include/plumed_master/colvar/../core/Action.h:27:
./GHBFIX.OsVSfP.cpp: In constructor ‘PLMD::colvar::GHBFIX::GHBFIX(const PLMD::ActionOptions&)’:
./GHBFIX.OsVSfP.cpp:139:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
139 |       plumed_assert(it<n)<<"itype ="<<it<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
./GHBFIX.OsVSfP.cpp:140:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
140 |       plumed_assert(jt<n)<<"jtype ="<<jt<<", should be smaller than "<<n;
|                     ~~^~
/home/runner/opt/include/plumed_master/colvar/../core/../tools/Exception.h:376:34: note: in definition of macro ‘plumed_assert’
376 | #define plumed_assert(test) if(!(test)) plumed_error() << PLMD::Exception::Assertion(#test)
|                                  ^~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : The GRID file you want to read: GRID, cannot be found!
[pkrvmf6wy0o8zjz:37043] *** Process received signal ***
[pkrvmf6wy0o8zjz:37043] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37043] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f609e845330]
[pkrvmf6wy0o8zjz:37043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f609e89eb2c]
[pkrvmf6wy0o8zjz:37043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f609e84527e]
[pkrvmf6wy0o8zjz:37043] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f609e8288ff]
[pkrvmf6wy0o8zjz:37043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f609eca5ff5]
[pkrvmf6wy0o8zjz:37043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f609ecbb0da]
[pkrvmf6wy0o8zjz:37043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f609eca5a55]
[pkrvmf6wy0o8zjz:37043] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f609eca5a6f]
[pkrvmf6wy0o8zjz:37043] [ 8] plumed_master(+0x146dd)[0x564f220166dd]
[pkrvmf6wy0o8zjz:37043] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f609e82a1ca]
[pkrvmf6wy0o8zjz:37043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f609e82a28b]
[pkrvmf6wy0o8zjz:37043] [11] plumed_master(+0x15365)[0x564f22017365]
[pkrvmf6wy0o8zjz:37043] *** End of error message ***
</pre>
{% endraw %}
