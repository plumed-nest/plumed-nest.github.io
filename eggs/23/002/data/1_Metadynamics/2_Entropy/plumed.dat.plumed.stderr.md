**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmmklqx:06417] *** Process received signal ***
[runnervmmklqx:06417] Signal: Aborted (6)
[runnervmmklqx:06417] Signal code:  (-6)
[runnervmmklqx:06417] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe378845330]
[runnervmmklqx:06417] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe37889eb2c]
[runnervmmklqx:06417] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe37884527e]
[runnervmmklqx:06417] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3788288ff]
[runnervmmklqx:06417] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe378ca5ff5]
[runnervmmklqx:06417] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe378cbb0da]
[runnervmmklqx:06417] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe378ca5a55]
[runnervmmklqx:06417] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe378ca5a6f]
[runnervmmklqx:06417] [ 8] plumed(+0x146dd)[0x55d9c2b166dd]
[runnervmmklqx:06417] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe37882a1ca]
[runnervmmklqx:06417] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe37882a28b]
[runnervmmklqx:06417] [11] plumed(+0x15365)[0x55d9c2b17365]
[runnervmmklqx:06417] *** End of error message ***
</pre>
{% endraw %}
