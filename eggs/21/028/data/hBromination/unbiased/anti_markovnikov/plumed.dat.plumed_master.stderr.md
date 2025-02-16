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
[fv-az787-589:64179] *** Process received signal ***
[fv-az787-589:64179] Signal: Aborted (6)
[fv-az787-589:64179] Signal code:  (-6)
[fv-az787-589:64179] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f32245330]
[fv-az787-589:64179] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f3229eb2c]
[fv-az787-589:64179] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f3224527e]
[fv-az787-589:64179] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f322288ff]
[fv-az787-589:64179] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f326a5ff5]
[fv-az787-589:64179] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f326bb0da]
[fv-az787-589:64179] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f326a5a55]
[fv-az787-589:64179] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f326a5a6f]
[fv-az787-589:64179] [ 8] plumed_master(+0x146dd)[0x55ed5e50f6dd]
[fv-az787-589:64179] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f3222a1ca]
[fv-az787-589:64179] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f3222a28b]
[fv-az787-589:64179] [11] plumed_master(+0x15365)[0x55ed5e510365]
[fv-az787-589:64179] *** End of error message ***
</pre>
{% endraw %}
