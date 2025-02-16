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
(tools/Keywords.cpp:385) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az1979-234:60223] *** Process received signal ***
[fv-az1979-234:60223] Signal: Aborted (6)
[fv-az1979-234:60223] Signal code:  (-6)
[fv-az1979-234:60223] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68d2245330]
[fv-az1979-234:60223] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68d229eb2c]
[fv-az1979-234:60223] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68d224527e]
[fv-az1979-234:60223] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68d22288ff]
[fv-az1979-234:60223] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68d26a5ff5]
[fv-az1979-234:60223] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68d26bb0da]
[fv-az1979-234:60223] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68d26a5a55]
[fv-az1979-234:60223] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68d26a5a6f]
[fv-az1979-234:60223] [ 8] plumed_master(+0x146dd)[0x55859fe056dd]
[fv-az1979-234:60223] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68d222a1ca]
[fv-az1979-234:60223] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68d222a28b]
[fv-az1979-234:60223] [11] plumed_master(+0x15365)[0x55859fe06365]
[fv-az1979-234:60223] *** End of error message ***
</pre>
{% endraw %}
