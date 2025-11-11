**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervmw9dnm:08859] *** Process received signal ***
[runnervmw9dnm:08859] Signal: Aborted (6)
[runnervmw9dnm:08859] Signal code:  (-6)
[runnervmw9dnm:08859] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2f28e45330]
[runnervmw9dnm:08859] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2f28e9eb2c]
[runnervmw9dnm:08859] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2f28e4527e]
[runnervmw9dnm:08859] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2f28e288ff]
[runnervmw9dnm:08859] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2f292a5ff5]
[runnervmw9dnm:08859] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2f292bb0da]
[runnervmw9dnm:08859] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2f292a5a55]
[runnervmw9dnm:08859] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2f292a5a6f]
[runnervmw9dnm:08859] [ 8] plumed_master(+0x146dd)[0x555d895af6dd]
[runnervmw9dnm:08859] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2f28e2a1ca]
[runnervmw9dnm:08859] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2f28e2a28b]
[runnervmw9dnm:08859] [11] plumed_master(+0x15365)[0x555d895b0365]
[runnervmw9dnm:08859] *** End of error message ***
</pre>
{% endraw %}
