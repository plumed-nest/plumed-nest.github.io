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
[runnervm0kj6c:05573] *** Process received signal ***
[runnervm0kj6c:05573] Signal: Aborted (6)
[runnervm0kj6c:05573] Signal code:  (-6)
[runnervm0kj6c:05573] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3296a45330]
[runnervm0kj6c:05573] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3296a9eb2c]
[runnervm0kj6c:05573] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3296a4527e]
[runnervm0kj6c:05573] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3296a288ff]
[runnervm0kj6c:05573] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3296ea5ff5]
[runnervm0kj6c:05573] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3296ebb0da]
[runnervm0kj6c:05573] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3296ea5a55]
[runnervm0kj6c:05573] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3296ea5a6f]
[runnervm0kj6c:05573] [ 8] plumed_master(+0x146dd)[0x5634dbc6e6dd]
[runnervm0kj6c:05573] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3296a2a1ca]
[runnervm0kj6c:05573] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3296a2a28b]
[runnervm0kj6c:05573] [11] plumed_master(+0x15365)[0x5634dbc6f365]
[runnervm0kj6c:05573] *** End of error message ***
</pre>
{% endraw %}
