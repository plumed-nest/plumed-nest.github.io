**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmi13qx:32360] *** Process received signal ***
[runnervmi13qx:32360] Signal: Aborted (6)
[runnervmi13qx:32360] Signal code:  (-6)
[runnervmi13qx:32360] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b8d445330]
[runnervmi13qx:32360] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b8d49eb2c]
[runnervmi13qx:32360] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b8d44527e]
[runnervmi13qx:32360] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b8d4288ff]
[runnervmi13qx:32360] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b8d8a5ff5]
[runnervmi13qx:32360] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b8d8bb0da]
[runnervmi13qx:32360] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b8d8a5a55]
[runnervmi13qx:32360] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b8d8a5a6f]
[runnervmi13qx:32360] [ 8] plumed_master(+0x146dd)[0x564e45f886dd]
[runnervmi13qx:32360] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b8d42a1ca]
[runnervmi13qx:32360] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b8d42a28b]
[runnervmi13qx:32360] [11] plumed_master(+0x15365)[0x564e45f89365]
[runnervmi13qx:32360] *** End of error message ***
</pre>
{% endraw %}
