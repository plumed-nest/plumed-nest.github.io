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
[fv-az1391-351:60679] *** Process received signal ***
[fv-az1391-351:60679] Signal: Aborted (6)
[fv-az1391-351:60679] Signal code:  (-6)
[fv-az1391-351:60679] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f260a845330]
[fv-az1391-351:60679] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f260a89eb2c]
[fv-az1391-351:60679] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f260a84527e]
[fv-az1391-351:60679] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f260a8288ff]
[fv-az1391-351:60679] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f260aca5ff5]
[fv-az1391-351:60679] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f260acbb0da]
[fv-az1391-351:60679] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f260aca5a55]
[fv-az1391-351:60679] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f260aca5a6f]
[fv-az1391-351:60679] [ 8] plumed_master(+0x146dd)[0x564e0906d6dd]
[fv-az1391-351:60679] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f260a82a1ca]
[fv-az1391-351:60679] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f260a82a28b]
[fv-az1391-351:60679] [11] plumed_master(+0x15365)[0x564e0906e365]
[fv-az1391-351:60679] *** End of error message ***
</pre>
{% endraw %}
