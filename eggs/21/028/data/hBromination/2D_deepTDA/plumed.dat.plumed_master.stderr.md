**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:476) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[fv-az1374-933:11655] *** Process received signal ***
[fv-az1374-933:11655] Signal: Aborted (6)
[fv-az1374-933:11655] Signal code:  (-6)
[fv-az1374-933:11655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99d4445330]
[fv-az1374-933:11655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99d449eb2c]
[fv-az1374-933:11655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99d444527e]
[fv-az1374-933:11655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99d44288ff]
[fv-az1374-933:11655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99d48a5ff5]
[fv-az1374-933:11655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99d48bb0da]
[fv-az1374-933:11655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99d48a5a55]
[fv-az1374-933:11655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99d48a5a6f]
[fv-az1374-933:11655] [ 8] plumed_master(+0x146dd)[0x55f40ee666dd]
[fv-az1374-933:11655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99d442a1ca]
[fv-az1374-933:11655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99d442a28b]
[fv-az1374-933:11655] [11] plumed_master(+0x15365)[0x55f40ee67365]
[fv-az1374-933:11655] *** End of error message ***
</pre>
{% endraw %}
