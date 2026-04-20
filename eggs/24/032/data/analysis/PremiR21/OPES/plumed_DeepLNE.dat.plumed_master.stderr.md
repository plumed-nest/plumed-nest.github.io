**Project ID:** [plumID:24.032]({{ '/' | absolute_url }}eggs/24/032/)  
Stderr for source:  analysis/PremiR21/OPES/plumed_DeepLNE.dat   
Download: [zipped raw stdout](plumed_DeepLNE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_DeepLNE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervmeorf1:04854] *** Process received signal ***
[runnervmeorf1:04854] Signal: Aborted (6)
[runnervmeorf1:04854] Signal code:  (-6)
[runnervmeorf1:04854] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f831e445330]
[runnervmeorf1:04854] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f831e49eb2c]
[runnervmeorf1:04854] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f831e44527e]
[runnervmeorf1:04854] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f831e4288ff]
[runnervmeorf1:04854] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f831e8a5ff5]
[runnervmeorf1:04854] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f831e8bb0da]
[runnervmeorf1:04854] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f831e8a5a55]
[runnervmeorf1:04854] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f831e8a5a6f]
[runnervmeorf1:04854] [ 8] plumed_master(+0x146dd)[0x55f2c2f2d6dd]
[runnervmeorf1:04854] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f831e42a1ca]
[runnervmeorf1:04854] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f831e42a28b]
[runnervmeorf1:04854] [11] plumed_master(+0x15365)[0x55f2c2f2e365]
[runnervmeorf1:04854] *** End of error message ***
</pre>
{% endraw %}
