**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:461) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvmf6wy0o8zjz:36695] *** Process received signal ***
[pkrvmf6wy0o8zjz:36695] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:36695] Signal code:  (-6)
[pkrvmf6wy0o8zjz:36695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe17a445330]
[pkrvmf6wy0o8zjz:36695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe17a49eb2c]
[pkrvmf6wy0o8zjz:36695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe17a44527e]
[pkrvmf6wy0o8zjz:36695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe17a4288ff]
[pkrvmf6wy0o8zjz:36695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe17a8a5ff5]
[pkrvmf6wy0o8zjz:36695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe17a8bb0da]
[pkrvmf6wy0o8zjz:36695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe17a8a5a55]
[pkrvmf6wy0o8zjz:36695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe17a8a5a6f]
[pkrvmf6wy0o8zjz:36695] [ 8] plumed_master(+0x146dd)[0x561b9eef56dd]
[pkrvmf6wy0o8zjz:36695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe17a42a1ca]
[pkrvmf6wy0o8zjz:36695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe17a42a28b]
[pkrvmf6wy0o8zjz:36695] [11] plumed_master(+0x15365)[0x561b9eef6365]
[pkrvmf6wy0o8zjz:36695] *** End of error message ***
</pre>
{% endraw %}
