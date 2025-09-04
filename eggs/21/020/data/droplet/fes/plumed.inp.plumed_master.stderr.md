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
from ./ReweightGeomFES.9FGhPJ.cpp:22:
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from ./ReweightGeomFES.9FGhPJ.cpp:24:
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
[pkrvm7jw40e0xgp:10220] *** Process received signal ***
[pkrvm7jw40e0xgp:10220] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10220] Signal code:  (-6)
[pkrvm7jw40e0xgp:10220] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0608045330]
[pkrvm7jw40e0xgp:10220] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f060809eb2c]
[pkrvm7jw40e0xgp:10220] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f060804527e]
[pkrvm7jw40e0xgp:10220] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06080288ff]
[pkrvm7jw40e0xgp:10220] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06084a5ff5]
[pkrvm7jw40e0xgp:10220] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06084bb0da]
[pkrvm7jw40e0xgp:10220] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06084a5a55]
[pkrvm7jw40e0xgp:10220] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06084a5a6f]
[pkrvm7jw40e0xgp:10220] [ 8] plumed_master(+0x146dd)[0x55f6662e36dd]
[pkrvm7jw40e0xgp:10220] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f060802a1ca]
[pkrvm7jw40e0xgp:10220] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f060802a28b]
[pkrvm7jw40e0xgp:10220] [11] plumed_master(+0x15365)[0x55f6662e4365]
[pkrvm7jw40e0xgp:10220] *** End of error message ***
</pre>
{% endraw %}
