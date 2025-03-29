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
[fv-az789-879:66041] *** Process received signal ***
[fv-az789-879:66041] Signal: Aborted (6)
[fv-az789-879:66041] Signal code:  (-6)
[fv-az789-879:66041] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd8b5845330]
[fv-az789-879:66041] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd8b589eb2c]
[fv-az789-879:66041] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd8b584527e]
[fv-az789-879:66041] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8b58288ff]
[fv-az789-879:66041] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8b5ca5ff5]
[fv-az789-879:66041] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8b5cbb0da]
[fv-az789-879:66041] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8b5ca5a55]
[fv-az789-879:66041] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8b5ca5a6f]
[fv-az789-879:66041] [ 8] plumed_master(+0x146dd)[0x55606ba4f6dd]
[fv-az789-879:66041] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd8b582a1ca]
[fv-az789-879:66041] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd8b582a28b]
[fv-az789-879:66041] [11] plumed_master(+0x15365)[0x55606ba50365]
[fv-az789-879:66041] *** End of error message ***
</pre>
{% endraw %}
