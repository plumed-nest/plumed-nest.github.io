**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[fv-az789-879:65986] *** Process received signal ***
[fv-az789-879:65986] Signal: Aborted (6)
[fv-az789-879:65986] Signal code:  (-6)
[fv-az789-879:65986] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34f5c45330]
[fv-az789-879:65986] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34f5c9eb2c]
[fv-az789-879:65986] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34f5c4527e]
[fv-az789-879:65986] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34f5c288ff]
[fv-az789-879:65986] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34f60a5ff5]
[fv-az789-879:65986] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34f60bb0da]
[fv-az789-879:65986] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34f60a5a55]
[fv-az789-879:65986] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34f60a5a6f]
[fv-az789-879:65986] [ 8] plumed_master(+0x146dd)[0x56099bb1e6dd]
[fv-az789-879:65986] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34f5c2a1ca]
[fv-az789-879:65986] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34f5c2a28b]
[fv-az789-879:65986] [11] plumed_master(+0x15365)[0x56099bb1f365]
[fv-az789-879:65986] *** End of error message ***
</pre>
{% endraw %}
