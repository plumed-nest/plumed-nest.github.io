**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[fv-az789-879:65931] *** Process received signal ***
[fv-az789-879:65931] Signal: Aborted (6)
[fv-az789-879:65931] Signal code:  (-6)
[fv-az789-879:65931] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b21445330]
[fv-az789-879:65931] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b2149eb2c]
[fv-az789-879:65931] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b2144527e]
[fv-az789-879:65931] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b214288ff]
[fv-az789-879:65931] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b218a5ff5]
[fv-az789-879:65931] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b218bb0da]
[fv-az789-879:65931] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b218a5a55]
[fv-az789-879:65931] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b218a5a6f]
[fv-az789-879:65931] [ 8] plumed_master(+0x146dd)[0x55b679b826dd]
[fv-az789-879:65931] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b2142a1ca]
[fv-az789-879:65931] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b2142a28b]
[fv-az789-879:65931] [11] plumed_master(+0x15365)[0x55b679b83365]
[fv-az789-879:65931] *** End of error message ***
</pre>
{% endraw %}
