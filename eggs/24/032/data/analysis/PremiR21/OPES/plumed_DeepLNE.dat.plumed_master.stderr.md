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
[runnervm76f27:04353] *** Process received signal ***
[runnervm76f27:04353] Signal: Aborted (6)
[runnervm76f27:04353] Signal code:  (-6)
[runnervm76f27:04353] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5acaa45330]
[runnervm76f27:04353] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5acaa9ec0c]
[runnervm76f27:04353] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5acaa4527e]
[runnervm76f27:04353] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5acaa288ff]
[runnervm76f27:04353] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5acaea5ff5]
[runnervm76f27:04353] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5acaebb0da]
[runnervm76f27:04353] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5acaea5a55]
[runnervm76f27:04353] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5acaea5a6f]
[runnervm76f27:04353] [ 8] plumed_master(+0x146dd)[0x558b610416dd]
[runnervm76f27:04353] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5acaa2a1ca]
[runnervm76f27:04353] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5acaa2a28b]
[runnervm76f27:04353] [11] plumed_master(+0x15365)[0x558b61042365]
[runnervm76f27:04353] *** End of error message ***
</pre>
{% endraw %}
