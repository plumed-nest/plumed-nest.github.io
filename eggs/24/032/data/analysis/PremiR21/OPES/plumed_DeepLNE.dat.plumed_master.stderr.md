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
[runnervmgx7h7:05456] *** Process received signal ***
[runnervmgx7h7:05456] Signal: Aborted (6)
[runnervmgx7h7:05456] Signal code:  (-6)
[runnervmgx7h7:05456] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d93845330]
[runnervmgx7h7:05456] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d9389ec0c]
[runnervmgx7h7:05456] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d9384527e]
[runnervmgx7h7:05456] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d938288ff]
[runnervmgx7h7:05456] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d93ca5ff5]
[runnervmgx7h7:05456] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d93cbb0da]
[runnervmgx7h7:05456] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d93ca5a55]
[runnervmgx7h7:05456] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d93ca5a6f]
[runnervmgx7h7:05456] [ 8] plumed_master(+0x146dd)[0x55aeb75516dd]
[runnervmgx7h7:05456] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d9382a1ca]
[runnervmgx7h7:05456] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d9382a28b]
[runnervmgx7h7:05456] [11] plumed_master(+0x15365)[0x55aeb7552365]
[runnervmgx7h7:05456] *** End of error message ***
</pre>
{% endraw %}
