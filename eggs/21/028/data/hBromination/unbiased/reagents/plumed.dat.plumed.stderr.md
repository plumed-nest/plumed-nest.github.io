**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[pkrvmxyh4eaekms:09396] *** Process received signal ***
[pkrvmxyh4eaekms:09396] Signal: Aborted (6)
[pkrvmxyh4eaekms:09396] Signal code:  (-6)
[pkrvmxyh4eaekms:09396] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9367a45330]
[pkrvmxyh4eaekms:09396] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9367a9eb2c]
[pkrvmxyh4eaekms:09396] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9367a4527e]
[pkrvmxyh4eaekms:09396] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9367a288ff]
[pkrvmxyh4eaekms:09396] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9367ea5ff5]
[pkrvmxyh4eaekms:09396] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9367ebb0da]
[pkrvmxyh4eaekms:09396] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9367ea5a55]
[pkrvmxyh4eaekms:09396] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9367ea5a6f]
[pkrvmxyh4eaekms:09396] [ 8] plumed(+0x146dd)[0x55d64a4a56dd]
[pkrvmxyh4eaekms:09396] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9367a2a1ca]
[pkrvmxyh4eaekms:09396] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9367a2a28b]
[pkrvmxyh4eaekms:09396] [11] plumed(+0x15365)[0x55d64a4a6365]
[pkrvmxyh4eaekms:09396] *** End of error message ***
</pre>
{% endraw %}
