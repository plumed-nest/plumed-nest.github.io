**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[pkrvmpptgkbjq6m:10612] *** Process received signal ***
[pkrvmpptgkbjq6m:10612] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10612] Signal code:  (-6)
[pkrvmpptgkbjq6m:10612] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6909a45330]
[pkrvmpptgkbjq6m:10612] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6909a9eb2c]
[pkrvmpptgkbjq6m:10612] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6909a4527e]
[pkrvmpptgkbjq6m:10612] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6909a288ff]
[pkrvmpptgkbjq6m:10612] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6909ea5ff5]
[pkrvmpptgkbjq6m:10612] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6909ebb0da]
[pkrvmpptgkbjq6m:10612] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6909ea5a55]
[pkrvmpptgkbjq6m:10612] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6909ea5a6f]
[pkrvmpptgkbjq6m:10612] [ 8] plumed(+0x146dd)[0x5593328536dd]
[pkrvmpptgkbjq6m:10612] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6909a2a1ca]
[pkrvmpptgkbjq6m:10612] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6909a2a28b]
[pkrvmpptgkbjq6m:10612] [11] plumed(+0x15365)[0x559332854365]
[pkrvmpptgkbjq6m:10612] *** End of error message ***
</pre>
{% endraw %}
