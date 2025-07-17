**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G4/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[pkrvmq0rgcvqdmg:11127] *** Process received signal ***
[pkrvmq0rgcvqdmg:11127] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11127] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11127] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6aea445330]
[pkrvmq0rgcvqdmg:11127] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6aea49eb2c]
[pkrvmq0rgcvqdmg:11127] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6aea44527e]
[pkrvmq0rgcvqdmg:11127] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6aea4288ff]
[pkrvmq0rgcvqdmg:11127] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6aea8a5ff5]
[pkrvmq0rgcvqdmg:11127] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6aea8bb0da]
[pkrvmq0rgcvqdmg:11127] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6aea8a5a55]
[pkrvmq0rgcvqdmg:11127] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6aea8a5a6f]
[pkrvmq0rgcvqdmg:11127] [ 8] plumed(+0x146dd)[0x55947c6196dd]
[pkrvmq0rgcvqdmg:11127] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6aea42a1ca]
[pkrvmq0rgcvqdmg:11127] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6aea42a28b]
[pkrvmq0rgcvqdmg:11127] [11] plumed(+0x15365)[0x55947c61a365]
[pkrvmq0rgcvqdmg:11127] *** End of error message ***
</pre>
{% endraw %}
