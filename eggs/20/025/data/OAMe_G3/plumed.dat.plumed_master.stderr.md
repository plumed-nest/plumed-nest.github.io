**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[pkrvmxyh4eaekms:12797] *** Process received signal ***
[pkrvmxyh4eaekms:12797] Signal: Aborted (6)
[pkrvmxyh4eaekms:12797] Signal code:  (-6)
[pkrvmxyh4eaekms:12797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2095e45330]
[pkrvmxyh4eaekms:12797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2095e9eb2c]
[pkrvmxyh4eaekms:12797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2095e4527e]
[pkrvmxyh4eaekms:12797] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2095e288ff]
[pkrvmxyh4eaekms:12797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f20962a5ff5]
[pkrvmxyh4eaekms:12797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f20962bb0da]
[pkrvmxyh4eaekms:12797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f20962a5a55]
[pkrvmxyh4eaekms:12797] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f20962a5a6f]
[pkrvmxyh4eaekms:12797] [ 8] plumed_master(+0x146dd)[0x55ff6610e6dd]
[pkrvmxyh4eaekms:12797] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2095e2a1ca]
[pkrvmxyh4eaekms:12797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2095e2a28b]
[pkrvmxyh4eaekms:12797] [11] plumed_master(+0x15365)[0x55ff6610f365]
[pkrvmxyh4eaekms:12797] *** End of error message ***
</pre>
{% endraw %}
