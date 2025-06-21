**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[pkrvmxyh4eaekms:09230] *** Process received signal ***
[pkrvmxyh4eaekms:09230] Signal: Aborted (6)
[pkrvmxyh4eaekms:09230] Signal code:  (-6)
[pkrvmxyh4eaekms:09230] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67ab045330]
[pkrvmxyh4eaekms:09230] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67ab09eb2c]
[pkrvmxyh4eaekms:09230] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67ab04527e]
[pkrvmxyh4eaekms:09230] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67ab0288ff]
[pkrvmxyh4eaekms:09230] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67ab4a5ff5]
[pkrvmxyh4eaekms:09230] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67ab4bb0da]
[pkrvmxyh4eaekms:09230] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67ab4a5a55]
[pkrvmxyh4eaekms:09230] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67ab4a5a6f]
[pkrvmxyh4eaekms:09230] [ 8] plumed(+0x146dd)[0x5588a0b156dd]
[pkrvmxyh4eaekms:09230] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67ab02a1ca]
[pkrvmxyh4eaekms:09230] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67ab02a28b]
[pkrvmxyh4eaekms:09230] [11] plumed(+0x15365)[0x5588a0b16365]
[pkrvmxyh4eaekms:09230] *** End of error message ***
</pre>
{% endraw %}
