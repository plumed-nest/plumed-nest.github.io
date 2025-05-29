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
from MultiANN_tanh.TF5bCT.cpp:22:
/home/runner/opt/include/plumed_master/function/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/function/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from MultiANN_tanh.TF5bCT.cpp:25:
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
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvmf6wy0o8zjz:61566] *** Process received signal ***
[pkrvmf6wy0o8zjz:61566] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:61566] Signal code:  (-6)
[pkrvmf6wy0o8zjz:61566] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6384245330]
[pkrvmf6wy0o8zjz:61566] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f638429eb2c]
[pkrvmf6wy0o8zjz:61566] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f638424527e]
[pkrvmf6wy0o8zjz:61566] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63842288ff]
[pkrvmf6wy0o8zjz:61566] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63846a5ff5]
[pkrvmf6wy0o8zjz:61566] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63846bb0da]
[pkrvmf6wy0o8zjz:61566] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63846a5a55]
[pkrvmf6wy0o8zjz:61566] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63846a5a6f]
[pkrvmf6wy0o8zjz:61566] [ 8] plumed_master(+0x146dd)[0x557c334986dd]
[pkrvmf6wy0o8zjz:61566] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f638422a1ca]
[pkrvmf6wy0o8zjz:61566] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f638422a28b]
[pkrvmf6wy0o8zjz:61566] [11] plumed_master(+0x15365)[0x557c33499365]
[pkrvmf6wy0o8zjz:61566] *** End of error message ***
</pre>
{% endraw %}
