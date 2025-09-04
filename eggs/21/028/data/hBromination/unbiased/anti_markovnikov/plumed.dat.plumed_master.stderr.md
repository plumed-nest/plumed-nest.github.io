**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvm7jw40e0xgp:12416] *** Process received signal ***
[pkrvm7jw40e0xgp:12416] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12416] Signal code:  (-6)
[pkrvm7jw40e0xgp:12416] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb6bce45330]
[pkrvm7jw40e0xgp:12416] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb6bce9eb2c]
[pkrvm7jw40e0xgp:12416] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb6bce4527e]
[pkrvm7jw40e0xgp:12416] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb6bce288ff]
[pkrvm7jw40e0xgp:12416] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6bd2a5ff5]
[pkrvm7jw40e0xgp:12416] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6bd2bb0da]
[pkrvm7jw40e0xgp:12416] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6bd2a5a55]
[pkrvm7jw40e0xgp:12416] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6bd2a5a6f]
[pkrvm7jw40e0xgp:12416] [ 8] plumed_master(+0x146dd)[0x55ba5cdd66dd]
[pkrvm7jw40e0xgp:12416] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb6bce2a1ca]
[pkrvm7jw40e0xgp:12416] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb6bce2a28b]
[pkrvm7jw40e0xgp:12416] [11] plumed_master(+0x15365)[0x55ba5cdd7365]
[pkrvm7jw40e0xgp:12416] *** End of error message ***
</pre>
{% endraw %}
