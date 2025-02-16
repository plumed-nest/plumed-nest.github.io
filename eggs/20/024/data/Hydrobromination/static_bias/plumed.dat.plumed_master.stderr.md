**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Hydrobromination/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:385) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az1112-175:67204] *** Process received signal ***
[fv-az1112-175:67204] Signal: Aborted (6)
[fv-az1112-175:67204] Signal code:  (-6)
[fv-az1112-175:67204] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe03245330]
[fv-az1112-175:67204] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe0329eb2c]
[fv-az1112-175:67204] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe0324527e]
[fv-az1112-175:67204] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe032288ff]
[fv-az1112-175:67204] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe036a5ff5]
[fv-az1112-175:67204] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe036bb0da]
[fv-az1112-175:67204] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe036a5a55]
[fv-az1112-175:67204] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe036a5a6f]
[fv-az1112-175:67204] [ 8] plumed_master(+0x146dd)[0x56467f2b56dd]
[fv-az1112-175:67204] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe0322a1ca]
[fv-az1112-175:67204] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe0322a28b]
[fv-az1112-175:67204] [11] plumed_master(+0x15365)[0x56467f2b6365]
[fv-az1112-175:67204] *** End of error message ***
</pre>
{% endraw %}
