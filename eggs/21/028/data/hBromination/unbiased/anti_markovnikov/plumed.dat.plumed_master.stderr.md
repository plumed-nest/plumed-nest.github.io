**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[fv-az1657-925:09363] *** Process received signal ***
[fv-az1657-925:09363] Signal: Aborted (6)
[fv-az1657-925:09363] Signal code:  (-6)
[fv-az1657-925:09363] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b65e45330]
[fv-az1657-925:09363] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b65e9eb2c]
[fv-az1657-925:09363] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b65e4527e]
[fv-az1657-925:09363] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b65e288ff]
[fv-az1657-925:09363] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b662a5ff5]
[fv-az1657-925:09363] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b662bb0da]
[fv-az1657-925:09363] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b662a5a55]
[fv-az1657-925:09363] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b662a5a6f]
[fv-az1657-925:09363] [ 8] plumed_master(+0x146dd)[0x557290c3f6dd]
[fv-az1657-925:09363] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b65e2a1ca]
[fv-az1657-925:09363] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b65e2a28b]
[fv-az1657-925:09363] [11] plumed_master(+0x15365)[0x557290c40365]
[fv-az1657-925:09363] *** End of error message ***
</pre>
{% endraw %}
