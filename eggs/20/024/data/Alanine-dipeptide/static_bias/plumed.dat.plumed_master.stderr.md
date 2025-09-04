**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[pkrvm7jw40e0xgp:11423] *** Process received signal ***
[pkrvm7jw40e0xgp:11423] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11423] Signal code:  (-6)
[pkrvm7jw40e0xgp:11423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb415845330]
[pkrvm7jw40e0xgp:11423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb41589eb2c]
[pkrvm7jw40e0xgp:11423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb41584527e]
[pkrvm7jw40e0xgp:11423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4158288ff]
[pkrvm7jw40e0xgp:11423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb415ca5ff5]
[pkrvm7jw40e0xgp:11423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb415cbb0da]
[pkrvm7jw40e0xgp:11423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb415ca5a55]
[pkrvm7jw40e0xgp:11423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb415ca5a6f]
[pkrvm7jw40e0xgp:11423] [ 8] plumed_master(+0x146dd)[0x5651a34d06dd]
[pkrvm7jw40e0xgp:11423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb41582a1ca]
[pkrvm7jw40e0xgp:11423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb41582a28b]
[pkrvm7jw40e0xgp:11423] [11] plumed_master(+0x15365)[0x5651a34d1365]
[pkrvm7jw40e0xgp:11423] *** End of error message ***
</pre>
{% endraw %}
