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
[fv-az1372-996:05677] *** Process received signal ***
[fv-az1372-996:05677] Signal: Aborted (6)
[fv-az1372-996:05677] Signal code:  (-6)
[fv-az1372-996:05677] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f75e4445330]
[fv-az1372-996:05677] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f75e449eb2c]
[fv-az1372-996:05677] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f75e444527e]
[fv-az1372-996:05677] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75e44288ff]
[fv-az1372-996:05677] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f75e48a5ff5]
[fv-az1372-996:05677] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f75e48bb0da]
[fv-az1372-996:05677] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f75e48a5a55]
[fv-az1372-996:05677] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f75e48a5a6f]
[fv-az1372-996:05677] [ 8] plumed_master(+0x146dd)[0x55e42ce4f6dd]
[fv-az1372-996:05677] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f75e442a1ca]
[fv-az1372-996:05677] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f75e442a28b]
[fv-az1372-996:05677] [11] plumed_master(+0x15365)[0x55e42ce50365]
[fv-az1372-996:05677] *** End of error message ***
</pre>
{% endraw %}
