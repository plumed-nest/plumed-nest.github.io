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
[fv-az787-589:64124] *** Process received signal ***
[fv-az787-589:64124] Signal: Aborted (6)
[fv-az787-589:64124] Signal code:  (-6)
[fv-az787-589:64124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9111a45330]
[fv-az787-589:64124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9111a9eb2c]
[fv-az787-589:64124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9111a4527e]
[fv-az787-589:64124] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9111a288ff]
[fv-az787-589:64124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9111ea5ff5]
[fv-az787-589:64124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9111ebb0da]
[fv-az787-589:64124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9111ea5a55]
[fv-az787-589:64124] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9111ea5a6f]
[fv-az787-589:64124] [ 8] plumed_master(+0x146dd)[0x55ce0a90c6dd]
[fv-az787-589:64124] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9111a2a1ca]
[fv-az787-589:64124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9111a2a28b]
[fv-az787-589:64124] [11] plumed_master(+0x15365)[0x55ce0a90d365]
[fv-az787-589:64124] *** End of error message ***
</pre>
{% endraw %}
