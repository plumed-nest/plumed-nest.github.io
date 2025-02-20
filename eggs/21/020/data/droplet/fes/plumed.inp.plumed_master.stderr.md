**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:385) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az816-356:11514] *** Process received signal ***
[fv-az816-356:11514] Signal: Aborted (6)
[fv-az816-356:11514] Signal code:  (-6)
[fv-az816-356:11514] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f470a245330]
[fv-az816-356:11514] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f470a29eb2c]
[fv-az816-356:11514] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f470a24527e]
[fv-az816-356:11514] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f470a2288ff]
[fv-az816-356:11514] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f470a6a5ff5]
[fv-az816-356:11514] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f470a6bb0da]
[fv-az816-356:11514] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f470a6a5a55]
[fv-az816-356:11514] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f470a6a5a6f]
[fv-az816-356:11514] [ 8] plumed_master(+0x146dd)[0x55ac391946dd]
[fv-az816-356:11514] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f470a22a1ca]
[fv-az816-356:11514] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f470a22a28b]
[fv-az816-356:11514] [11] plumed_master(+0x15365)[0x55ac39195365]
[fv-az816-356:11514] *** End of error message ***
</pre>
{% endraw %}
