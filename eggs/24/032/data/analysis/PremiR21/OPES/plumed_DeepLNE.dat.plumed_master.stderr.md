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
[runnervmvrwv9:04723] *** Process received signal ***
[runnervmvrwv9:04723] Signal: Aborted (6)
[runnervmvrwv9:04723] Signal code:  (-6)
[runnervmvrwv9:04723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa704045330]
[runnervmvrwv9:04723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa70409eb2c]
[runnervmvrwv9:04723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa70404527e]
[runnervmvrwv9:04723] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7040288ff]
[runnervmvrwv9:04723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7044a5ff5]
[runnervmvrwv9:04723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7044bb0da]
[runnervmvrwv9:04723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7044a5a55]
[runnervmvrwv9:04723] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7044a5a6f]
[runnervmvrwv9:04723] [ 8] plumed_master(+0x146dd)[0x559201b986dd]
[runnervmvrwv9:04723] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa70402a1ca]
[runnervmvrwv9:04723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa70402a28b]
[runnervmvrwv9:04723] [11] plumed_master(+0x15365)[0x559201b99365]
[runnervmvrwv9:04723] *** End of error message ***
</pre>
{% endraw %}
