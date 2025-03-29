**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
Stderr for source:  Alanine-dipeptide/static_bias/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:372) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az1701-508:65795] *** Process received signal ***
[fv-az1701-508:65795] Signal: Aborted (6)
[fv-az1701-508:65795] Signal code:  (-6)
[fv-az1701-508:65795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f261d845330]
[fv-az1701-508:65795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f261d89eb2c]
[fv-az1701-508:65795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f261d84527e]
[fv-az1701-508:65795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f261d8288ff]
[fv-az1701-508:65795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f261dca5ff5]
[fv-az1701-508:65795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f261dcbb0da]
[fv-az1701-508:65795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f261dca5a55]
[fv-az1701-508:65795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f261dca5a6f]
[fv-az1701-508:65795] [ 8] plumed_master(+0x146dd)[0x559fa32be6dd]
[fv-az1701-508:65795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f261d82a1ca]
[fv-az1701-508:65795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f261d82a28b]
[fv-az1701-508:65795] [11] plumed_master(+0x15365)[0x559fa32bf365]
[fv-az1701-508:65795] *** End of error message ***
</pre>
{% endraw %}
