**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[fv-az787-589:64161] *** Process received signal ***
[fv-az787-589:64161] Signal: Aborted (6)
[fv-az787-589:64161] Signal code:  (-6)
[fv-az787-589:64161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd3e8a45330]
[fv-az787-589:64161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd3e8a9eb2c]
[fv-az787-589:64161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd3e8a4527e]
[fv-az787-589:64161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3e8a288ff]
[fv-az787-589:64161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3e8ea5ff5]
[fv-az787-589:64161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3e8ebb0da]
[fv-az787-589:64161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3e8ea5a55]
[fv-az787-589:64161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3e8ea5a6f]
[fv-az787-589:64161] [ 8] plumed(+0x146dd)[0x55ff23d966dd]
[fv-az787-589:64161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd3e8a2a1ca]
[fv-az787-589:64161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd3e8a2a28b]
[fv-az787-589:64161] [11] plumed(+0x15365)[0x55ff23d97365]
[fv-az787-589:64161] *** End of error message ***
</pre>
{% endraw %}
