**Project ID:** [plumID:24.032]({{ '/' | absolute_url }}eggs/24/032/)  
Stderr for source:  analysis/PremiR21/OPES/plumed_DeepLNE.dat   
Download: [zipped raw stdout](plumed_DeepLNE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_DeepLNE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
In file included from /home/runner/opt/include/plumed_master/function/../core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/function/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/function/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/function/Function.h:25,
from MultiANN_tanh.cRX2EM.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/function/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from MultiANN_tanh.cRX2EM.cpp:25:
/home/runner/opt/include/plumed_master/tools/Matrix.h:100: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
100 | #pragma acc enter data copyin(this[0:1],sz,data[0:sz])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:103: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
103 | #pragma acc exit data delete(data[0:sz],sz,this[0:1])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:117: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
117 | #pragma acc enter data copyin(this[0:1])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:123: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
123 | #pragma acc exit data delete( this[0:1])
|
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvmpptgkbjq6m:06741] *** Process received signal ***
[pkrvmpptgkbjq6m:06741] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06741] Signal code:  (-6)
[pkrvmpptgkbjq6m:06741] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e8d445330]
[pkrvmpptgkbjq6m:06741] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e8d49eb2c]
[pkrvmpptgkbjq6m:06741] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e8d44527e]
[pkrvmpptgkbjq6m:06741] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e8d4288ff]
[pkrvmpptgkbjq6m:06741] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e8d8a5ff5]
[pkrvmpptgkbjq6m:06741] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e8d8bb0da]
[pkrvmpptgkbjq6m:06741] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e8d8a5a55]
[pkrvmpptgkbjq6m:06741] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e8d8a5a6f]
[pkrvmpptgkbjq6m:06741] [ 8] plumed_master(+0x146dd)[0x55aa5f7a16dd]
[pkrvmpptgkbjq6m:06741] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e8d42a1ca]
[pkrvmpptgkbjq6m:06741] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e8d42a28b]
[pkrvmpptgkbjq6m:06741] [11] plumed_master(+0x15365)[0x55aa5f7a2365]
[pkrvmpptgkbjq6m:06741] *** End of error message ***
</pre>
{% endraw %}
