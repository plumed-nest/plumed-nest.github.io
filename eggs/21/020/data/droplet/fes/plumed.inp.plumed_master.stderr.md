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
from ./ReweightGeomFES.OM05M6.cpp:22:
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from ./ReweightGeomFES.OM05M6.cpp:24:
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
[pkrvmbietmlfzoi:12015] *** Process received signal ***
[pkrvmbietmlfzoi:12015] Signal: Aborted (6)
[pkrvmbietmlfzoi:12015] Signal code:  (-6)
[pkrvmbietmlfzoi:12015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6d9845330]
[pkrvmbietmlfzoi:12015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6d989eb2c]
[pkrvmbietmlfzoi:12015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6d984527e]
[pkrvmbietmlfzoi:12015] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6d98288ff]
[pkrvmbietmlfzoi:12015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6d9ca5ff5]
[pkrvmbietmlfzoi:12015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6d9cbb0da]
[pkrvmbietmlfzoi:12015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6d9ca5a55]
[pkrvmbietmlfzoi:12015] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6d9ca5a6f]
[pkrvmbietmlfzoi:12015] [ 8] plumed_master(+0x146dd)[0x561ce4f4b6dd]
[pkrvmbietmlfzoi:12015] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6d982a1ca]
[pkrvmbietmlfzoi:12015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6d982a28b]
[pkrvmbietmlfzoi:12015] [11] plumed_master(+0x15365)[0x561ce4f4c365]
[pkrvmbietmlfzoi:12015] *** End of error message ***
</pre>
{% endraw %}
