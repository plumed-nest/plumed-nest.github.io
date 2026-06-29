**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmmklqx:05970] *** Process received signal ***
[runnervmmklqx:05970] Signal: Aborted (6)
[runnervmmklqx:05970] Signal code:  (-6)
[runnervmmklqx:05970] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9239445330]
[runnervmmklqx:05970] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f923949eb2c]
[runnervmmklqx:05970] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f923944527e]
[runnervmmklqx:05970] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92394288ff]
[runnervmmklqx:05970] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92398a5ff5]
[runnervmmklqx:05970] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92398bb0da]
[runnervmmklqx:05970] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92398a5a55]
[runnervmmklqx:05970] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92398a5a6f]
[runnervmmklqx:05970] [ 8] plumed_master(+0x146dd)[0x556ba237e6dd]
[runnervmmklqx:05970] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f923942a1ca]
[runnervmmklqx:05970] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f923942a28b]
[runnervmmklqx:05970] [11] plumed_master(+0x15365)[0x556ba237f365]
[runnervmmklqx:05970] *** End of error message ***
</pre>
{% endraw %}
