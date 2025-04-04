**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az2207-973:09653] *** Process received signal ***
[fv-az2207-973:09653] Signal: Aborted (6)
[fv-az2207-973:09653] Signal code:  (-6)
[fv-az2207-973:09653] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa153245330]
[fv-az2207-973:09653] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa15329eb2c]
[fv-az2207-973:09653] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa15324527e]
[fv-az2207-973:09653] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1532288ff]
[fv-az2207-973:09653] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1536a5ff5]
[fv-az2207-973:09653] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1536bb0da]
[fv-az2207-973:09653] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1536a5a55]
[fv-az2207-973:09653] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1536a5a6f]
[fv-az2207-973:09653] [ 8] plumed_master(+0x146dd)[0x56019efd16dd]
[fv-az2207-973:09653] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa15322a1ca]
[fv-az2207-973:09653] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa15322a28b]
[fv-az2207-973:09653] [11] plumed_master(+0x15365)[0x56019efd2365]
[fv-az2207-973:09653] *** End of error message ***
</pre>
{% endraw %}
