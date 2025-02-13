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
[fv-az1280-696:11401] *** Process received signal ***
[fv-az1280-696:11401] Signal: Aborted (6)
[fv-az1280-696:11401] Signal code:  (-6)
[fv-az1280-696:11401] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f65e8c45330]
[fv-az1280-696:11401] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f65e8c9eb2c]
[fv-az1280-696:11401] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f65e8c4527e]
[fv-az1280-696:11401] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f65e8c288ff]
[fv-az1280-696:11401] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65e90a5ff5]
[fv-az1280-696:11401] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65e90bb0da]
[fv-az1280-696:11401] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65e90a5a55]
[fv-az1280-696:11401] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65e90a5a6f]
[fv-az1280-696:11401] [ 8] plumed_master(+0x146dd)[0x5608b9f4a6dd]
[fv-az1280-696:11401] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f65e8c2a1ca]
[fv-az1280-696:11401] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f65e8c2a28b]
[fv-az1280-696:11401] [11] plumed_master(+0x15365)[0x5608b9f4b365]
[fv-az1280-696:11401] *** End of error message ***
</pre>
{% endraw %}
