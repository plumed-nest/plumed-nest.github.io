**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[fv-az789-879:65968] *** Process received signal ***
[fv-az789-879:65968] Signal: Aborted (6)
[fv-az789-879:65968] Signal code:  (-6)
[fv-az789-879:65968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c2e645330]
[fv-az789-879:65968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c2e69eb2c]
[fv-az789-879:65968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c2e64527e]
[fv-az789-879:65968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c2e6288ff]
[fv-az789-879:65968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c2eaa5ff5]
[fv-az789-879:65968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c2eabb0da]
[fv-az789-879:65968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c2eaa5a55]
[fv-az789-879:65968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c2eaa5a6f]
[fv-az789-879:65968] [ 8] plumed(+0x146dd)[0x557dba6596dd]
[fv-az789-879:65968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c2e62a1ca]
[fv-az789-879:65968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c2e62a28b]
[fv-az789-879:65968] [11] plumed(+0x15365)[0x557dba65a365]
[fv-az789-879:65968] *** End of error message ***
</pre>
{% endraw %}
