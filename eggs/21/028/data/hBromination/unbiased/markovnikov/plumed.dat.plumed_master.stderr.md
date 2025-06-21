**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[pkrvmxyh4eaekms:09359] *** Process received signal ***
[pkrvmxyh4eaekms:09359] Signal: Aborted (6)
[pkrvmxyh4eaekms:09359] Signal code:  (-6)
[pkrvmxyh4eaekms:09359] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f58fba45330]
[pkrvmxyh4eaekms:09359] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f58fba9eb2c]
[pkrvmxyh4eaekms:09359] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f58fba4527e]
[pkrvmxyh4eaekms:09359] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58fba288ff]
[pkrvmxyh4eaekms:09359] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58fbea5ff5]
[pkrvmxyh4eaekms:09359] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58fbebb0da]
[pkrvmxyh4eaekms:09359] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58fbea5a55]
[pkrvmxyh4eaekms:09359] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58fbea5a6f]
[pkrvmxyh4eaekms:09359] [ 8] plumed_master(+0x146dd)[0x564a4c1106dd]
[pkrvmxyh4eaekms:09359] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f58fba2a1ca]
[pkrvmxyh4eaekms:09359] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f58fba2a28b]
[pkrvmxyh4eaekms:09359] [11] plumed_master(+0x15365)[0x564a4c111365]
[pkrvmxyh4eaekms:09359] *** End of error message ***
</pre>
{% endraw %}
