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
[pkrvmxyh4eaekms:09304] *** Process received signal ***
[pkrvmxyh4eaekms:09304] Signal: Aborted (6)
[pkrvmxyh4eaekms:09304] Signal code:  (-6)
[pkrvmxyh4eaekms:09304] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5492c45330]
[pkrvmxyh4eaekms:09304] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5492c9eb2c]
[pkrvmxyh4eaekms:09304] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5492c4527e]
[pkrvmxyh4eaekms:09304] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5492c288ff]
[pkrvmxyh4eaekms:09304] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f54930a5ff5]
[pkrvmxyh4eaekms:09304] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f54930bb0da]
[pkrvmxyh4eaekms:09304] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f54930a5a55]
[pkrvmxyh4eaekms:09304] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f54930a5a6f]
[pkrvmxyh4eaekms:09304] [ 8] plumed_master(+0x146dd)[0x559279c4a6dd]
[pkrvmxyh4eaekms:09304] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5492c2a1ca]
[pkrvmxyh4eaekms:09304] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5492c2a28b]
[pkrvmxyh4eaekms:09304] [11] plumed_master(+0x15365)[0x559279c4b365]
[pkrvmxyh4eaekms:09304] *** End of error message ***
</pre>
{% endraw %}
