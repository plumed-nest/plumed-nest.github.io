**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
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
[pkrvmxyh4eaekms:09248] *** Process received signal ***
[pkrvmxyh4eaekms:09248] Signal: Aborted (6)
[pkrvmxyh4eaekms:09248] Signal code:  (-6)
[pkrvmxyh4eaekms:09248] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f792a245330]
[pkrvmxyh4eaekms:09248] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f792a29eb2c]
[pkrvmxyh4eaekms:09248] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f792a24527e]
[pkrvmxyh4eaekms:09248] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f792a2288ff]
[pkrvmxyh4eaekms:09248] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f792a6a5ff5]
[pkrvmxyh4eaekms:09248] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f792a6bb0da]
[pkrvmxyh4eaekms:09248] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f792a6a5a55]
[pkrvmxyh4eaekms:09248] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f792a6a5a6f]
[pkrvmxyh4eaekms:09248] [ 8] plumed_master(+0x146dd)[0x555afcddb6dd]
[pkrvmxyh4eaekms:09248] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f792a22a1ca]
[pkrvmxyh4eaekms:09248] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f792a22a28b]
[pkrvmxyh4eaekms:09248] [11] plumed_master(+0x15365)[0x555afcddc365]
[pkrvmxyh4eaekms:09248] *** End of error message ***
</pre>
{% endraw %}
