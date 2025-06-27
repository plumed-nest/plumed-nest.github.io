**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
In file included from /home/runner/opt/include/plumed_master/bias/../core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/bias/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/bias/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/bias/ReweightBase.h:25,
from ./ReweightGeomFES.qf9UzN.cpp:22:
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from ./ReweightGeomFES.qf9UzN.cpp:24:
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
[pkrvmbietmlfzoi:65646] *** Process received signal ***
[pkrvmbietmlfzoi:65646] Signal: Aborted (6)
[pkrvmbietmlfzoi:65646] Signal code:  (-6)
[pkrvmbietmlfzoi:65646] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc954e45330]
[pkrvmbietmlfzoi:65646] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc954e9eb2c]
[pkrvmbietmlfzoi:65646] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc954e4527e]
[pkrvmbietmlfzoi:65646] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc954e288ff]
[pkrvmbietmlfzoi:65646] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9552a5ff5]
[pkrvmbietmlfzoi:65646] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9552bb0da]
[pkrvmbietmlfzoi:65646] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9552a5a55]
[pkrvmbietmlfzoi:65646] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9552a5a6f]
[pkrvmbietmlfzoi:65646] [ 8] plumed_master(+0x146dd)[0x557bf3c606dd]
[pkrvmbietmlfzoi:65646] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc954e2a1ca]
[pkrvmbietmlfzoi:65646] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc954e2a28b]
[pkrvmbietmlfzoi:65646] [11] plumed_master(+0x15365)[0x557bf3c61365]
[pkrvmbietmlfzoi:65646] *** End of error message ***
</pre>
{% endraw %}
