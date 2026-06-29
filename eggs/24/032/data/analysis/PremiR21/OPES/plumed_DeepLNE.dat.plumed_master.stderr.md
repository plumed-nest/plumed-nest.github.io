**Project ID:** [plumID:24.032]({{ '/' | absolute_url }}eggs/24/032/)  
Stderr for source:  analysis/PremiR21/OPES/plumed_DeepLNE.dat   
Download: [zipped raw stdout](plumed_DeepLNE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_DeepLNE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervmmklqx:06292] *** Process received signal ***
[runnervmmklqx:06292] Signal: Aborted (6)
[runnervmmklqx:06292] Signal code:  (-6)
[runnervmmklqx:06292] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f951a645330]
[runnervmmklqx:06292] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f951a69eb2c]
[runnervmmklqx:06292] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f951a64527e]
[runnervmmklqx:06292] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f951a6288ff]
[runnervmmklqx:06292] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f951aaa5ff5]
[runnervmmklqx:06292] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f951aabb0da]
[runnervmmklqx:06292] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f951aaa5a55]
[runnervmmklqx:06292] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f951aaa5a6f]
[runnervmmklqx:06292] [ 8] plumed_master(+0x146dd)[0x560db61166dd]
[runnervmmklqx:06292] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f951a62a1ca]
[runnervmmklqx:06292] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f951a62a28b]
[runnervmmklqx:06292] [11] plumed_master(+0x15365)[0x560db6117365]
[runnervmmklqx:06292] *** End of error message ***
</pre>
{% endraw %}
