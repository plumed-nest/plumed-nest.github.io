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
[pkrvmberfyhpb9w:06173] *** Process received signal ***
[pkrvmberfyhpb9w:06173] Signal: Aborted (6)
[pkrvmberfyhpb9w:06173] Signal code:  (-6)
[pkrvmberfyhpb9w:06173] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5266445330]
[pkrvmberfyhpb9w:06173] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f526649eb2c]
[pkrvmberfyhpb9w:06173] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f526644527e]
[pkrvmberfyhpb9w:06173] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52664288ff]
[pkrvmberfyhpb9w:06173] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f52668a5ff5]
[pkrvmberfyhpb9w:06173] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f52668bb0da]
[pkrvmberfyhpb9w:06173] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f52668a5a55]
[pkrvmberfyhpb9w:06173] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f52668a5a6f]
[pkrvmberfyhpb9w:06173] [ 8] plumed_master(+0x146dd)[0x55edbefc36dd]
[pkrvmberfyhpb9w:06173] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f526642a1ca]
[pkrvmberfyhpb9w:06173] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f526642a28b]
[pkrvmberfyhpb9w:06173] [11] plumed_master(+0x15365)[0x55edbefc4365]
[pkrvmberfyhpb9w:06173] *** End of error message ***
</pre>
{% endraw %}
