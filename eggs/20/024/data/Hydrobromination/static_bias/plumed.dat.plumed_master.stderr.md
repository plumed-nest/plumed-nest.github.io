**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Hydrobromination/static_bias/plumed.dat   
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
[pkrvm7jw40e0xgp:11508] *** Process received signal ***
[pkrvm7jw40e0xgp:11508] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11508] Signal code:  (-6)
[pkrvm7jw40e0xgp:11508] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2662645330]
[pkrvm7jw40e0xgp:11508] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f266269eb2c]
[pkrvm7jw40e0xgp:11508] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f266264527e]
[pkrvm7jw40e0xgp:11508] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f26626288ff]
[pkrvm7jw40e0xgp:11508] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2662aa5ff5]
[pkrvm7jw40e0xgp:11508] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2662abb0da]
[pkrvm7jw40e0xgp:11508] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2662aa5a55]
[pkrvm7jw40e0xgp:11508] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2662aa5a6f]
[pkrvm7jw40e0xgp:11508] [ 8] plumed_master(+0x146dd)[0x564535cbe6dd]
[pkrvm7jw40e0xgp:11508] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f266262a1ca]
[pkrvm7jw40e0xgp:11508] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f266262a28b]
[pkrvm7jw40e0xgp:11508] [11] plumed_master(+0x15365)[0x564535cbf365]
[pkrvm7jw40e0xgp:11508] *** End of error message ***
</pre>
{% endraw %}
