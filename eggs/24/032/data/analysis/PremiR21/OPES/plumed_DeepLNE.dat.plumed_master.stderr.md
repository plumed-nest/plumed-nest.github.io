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
[runnervmkj6or:04566] *** Process received signal ***
[runnervmkj6or:04566] Signal: Aborted (6)
[runnervmkj6or:04566] Signal code:  (-6)
[runnervmkj6or:04566] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2654a45330]
[runnervmkj6or:04566] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2654a9eb2c]
[runnervmkj6or:04566] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2654a4527e]
[runnervmkj6or:04566] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2654a288ff]
[runnervmkj6or:04566] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2654ea5ff5]
[runnervmkj6or:04566] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2654ebb0da]
[runnervmkj6or:04566] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2654ea5a55]
[runnervmkj6or:04566] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2654ea5a6f]
[runnervmkj6or:04566] [ 8] plumed_master(+0x146dd)[0x55d38a0cd6dd]
[runnervmkj6or:04566] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2654a2a1ca]
[runnervmkj6or:04566] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2654a2a28b]
[runnervmkj6or:04566] [11] plumed_master(+0x15365)[0x55d38a0ce365]
[runnervmkj6or:04566] *** End of error message ***
</pre>
{% endraw %}
