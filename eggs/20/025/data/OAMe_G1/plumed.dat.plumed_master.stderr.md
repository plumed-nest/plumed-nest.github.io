**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[fv-az1781-845:64609] *** Process received signal ***
[fv-az1781-845:64609] Signal: Aborted (6)
[fv-az1781-845:64609] Signal code:  (-6)
[fv-az1781-845:64609] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fae45445330]
[fv-az1781-845:64609] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fae4549eb2c]
[fv-az1781-845:64609] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fae4544527e]
[fv-az1781-845:64609] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fae454288ff]
[fv-az1781-845:64609] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fae458a5ff5]
[fv-az1781-845:64609] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fae458bb0da]
[fv-az1781-845:64609] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fae458a5a55]
[fv-az1781-845:64609] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fae458a5a6f]
[fv-az1781-845:64609] [ 8] plumed_master(+0x146dd)[0x562b8803c6dd]
[fv-az1781-845:64609] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fae4542a1ca]
[fv-az1781-845:64609] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fae4542a28b]
[fv-az1781-845:64609] [11] plumed_master(+0x15365)[0x562b8803d365]
[fv-az1781-845:64609] *** End of error message ***
</pre>
{% endraw %}
