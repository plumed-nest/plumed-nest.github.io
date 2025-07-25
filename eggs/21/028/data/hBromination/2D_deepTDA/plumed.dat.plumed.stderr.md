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
[pkrvmpptgkbjq6m:10444] *** Process received signal ***
[pkrvmpptgkbjq6m:10444] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10444] Signal code:  (-6)
[pkrvmpptgkbjq6m:10444] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1fcf645330]
[pkrvmpptgkbjq6m:10444] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1fcf69eb2c]
[pkrvmpptgkbjq6m:10444] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1fcf64527e]
[pkrvmpptgkbjq6m:10444] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1fcf6288ff]
[pkrvmpptgkbjq6m:10444] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1fcfaa5ff5]
[pkrvmpptgkbjq6m:10444] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1fcfabb0da]
[pkrvmpptgkbjq6m:10444] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1fcfaa5a55]
[pkrvmpptgkbjq6m:10444] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1fcfaa5a6f]
[pkrvmpptgkbjq6m:10444] [ 8] plumed(+0x146dd)[0x562870b266dd]
[pkrvmpptgkbjq6m:10444] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1fcf62a1ca]
[pkrvmpptgkbjq6m:10444] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1fcf62a28b]
[pkrvmpptgkbjq6m:10444] [11] plumed(+0x15365)[0x562870b27365]
[pkrvmpptgkbjq6m:10444] *** End of error message ***
</pre>
{% endraw %}
