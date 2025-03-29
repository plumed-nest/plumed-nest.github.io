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
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az789-879:61219] *** Process received signal ***
[fv-az789-879:61219] Signal: Aborted (6)
[fv-az789-879:61219] Signal code:  (-6)
[fv-az789-879:61219] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbfc3045330]
[fv-az789-879:61219] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbfc309eb2c]
[fv-az789-879:61219] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbfc304527e]
[fv-az789-879:61219] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbfc30288ff]
[fv-az789-879:61219] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbfc34a5ff5]
[fv-az789-879:61219] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbfc34bb0da]
[fv-az789-879:61219] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbfc34a5a55]
[fv-az789-879:61219] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbfc34a5a6f]
[fv-az789-879:61219] [ 8] plumed_master(+0x146dd)[0x55ac023856dd]
[fv-az789-879:61219] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbfc302a1ca]
[fv-az789-879:61219] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbfc302a28b]
[fv-az789-879:61219] [11] plumed_master(+0x15365)[0x55ac02386365]
[fv-az789-879:61219] *** End of error message ***
</pre>
{% endraw %}
