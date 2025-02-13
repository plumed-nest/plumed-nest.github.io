**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G4/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[fv-az1280-696:12350] *** Process received signal ***
[fv-az1280-696:12350] Signal: Aborted (6)
[fv-az1280-696:12350] Signal code:  (-6)
[fv-az1280-696:12350] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1b2e445330]
[fv-az1280-696:12350] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1b2e49eb2c]
[fv-az1280-696:12350] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1b2e44527e]
[fv-az1280-696:12350] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1b2e4288ff]
[fv-az1280-696:12350] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1b2e8a5ff5]
[fv-az1280-696:12350] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1b2e8bb0da]
[fv-az1280-696:12350] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1b2e8a5a55]
[fv-az1280-696:12350] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1b2e8a5a6f]
[fv-az1280-696:12350] [ 8] plumed(+0x146dd)[0x5586d98126dd]
[fv-az1280-696:12350] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1b2e42a1ca]
[fv-az1280-696:12350] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1b2e42a28b]
[fv-az1280-696:12350] [11] plumed(+0x15365)[0x5586d9813365]
[fv-az1280-696:12350] *** End of error message ***
</pre>
{% endraw %}
