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
[fv-az1277-646:66842] *** Process received signal ***
[fv-az1277-646:66842] Signal: Aborted (6)
[fv-az1277-646:66842] Signal code:  (-6)
[fv-az1277-646:66842] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd397845330]
[fv-az1277-646:66842] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd39789eb2c]
[fv-az1277-646:66842] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd39784527e]
[fv-az1277-646:66842] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3978288ff]
[fv-az1277-646:66842] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd397ca5ff5]
[fv-az1277-646:66842] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd397cbb0da]
[fv-az1277-646:66842] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd397ca5a55]
[fv-az1277-646:66842] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd397ca5a6f]
[fv-az1277-646:66842] [ 8] plumed_master(+0x146dd)[0x55a4d25086dd]
[fv-az1277-646:66842] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd39782a1ca]
[fv-az1277-646:66842] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd39782a28b]
[fv-az1277-646:66842] [11] plumed_master(+0x15365)[0x55a4d2509365]
[fv-az1277-646:66842] *** End of error message ***
</pre>
{% endraw %}
