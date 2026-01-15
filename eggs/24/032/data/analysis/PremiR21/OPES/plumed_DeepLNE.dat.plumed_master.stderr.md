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
[runnervmi13qx:31995] *** Process received signal ***
[runnervmi13qx:31995] Signal: Aborted (6)
[runnervmi13qx:31995] Signal code:  (-6)
[runnervmi13qx:31995] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbdc245330]
[runnervmi13qx:31995] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbdc29eb2c]
[runnervmi13qx:31995] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbdc24527e]
[runnervmi13qx:31995] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbdc2288ff]
[runnervmi13qx:31995] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbdc6a5ff5]
[runnervmi13qx:31995] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbdc6bb0da]
[runnervmi13qx:31995] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbdc6a5a55]
[runnervmi13qx:31995] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbdc6a5a6f]
[runnervmi13qx:31995] [ 8] plumed_master(+0x146dd)[0x5617bf4e06dd]
[runnervmi13qx:31995] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbdc22a1ca]
[runnervmi13qx:31995] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbdc22a28b]
[runnervmi13qx:31995] [11] plumed_master(+0x15365)[0x5617bf4e1365]
[runnervmi13qx:31995] *** End of error message ***
</pre>
{% endraw %}
