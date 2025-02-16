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
[fv-az787-589:64271] *** Process received signal ***
[fv-az787-589:64271] Signal: Aborted (6)
[fv-az787-589:64271] Signal code:  (-6)
[fv-az787-589:64271] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f01be045330]
[fv-az787-589:64271] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f01be09eb2c]
[fv-az787-589:64271] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f01be04527e]
[fv-az787-589:64271] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01be0288ff]
[fv-az787-589:64271] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01be4a5ff5]
[fv-az787-589:64271] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01be4bb0da]
[fv-az787-589:64271] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01be4a5a55]
[fv-az787-589:64271] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01be4a5a6f]
[fv-az787-589:64271] [ 8] plumed(+0x146dd)[0x55c43c0216dd]
[fv-az787-589:64271] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f01be02a1ca]
[fv-az787-589:64271] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f01be02a28b]
[fv-az787-589:64271] [11] plumed(+0x15365)[0x55c43c022365]
[fv-az787-589:64271] *** End of error message ***
</pre>
{% endraw %}
