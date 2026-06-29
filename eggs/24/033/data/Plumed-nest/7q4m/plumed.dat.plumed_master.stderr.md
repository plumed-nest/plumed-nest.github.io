**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmmklqx:06123] *** Process received signal ***
[runnervmmklqx:06123] Signal: Aborted (6)
[runnervmmklqx:06123] Signal code:  (-6)
[runnervmmklqx:06123] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48e6845330]
[runnervmmklqx:06123] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48e689eb2c]
[runnervmmklqx:06123] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48e684527e]
[runnervmmklqx:06123] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48e68288ff]
[runnervmmklqx:06123] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48e6ca5ff5]
[runnervmmklqx:06123] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48e6cbb0da]
[runnervmmklqx:06123] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48e6ca5a55]
[runnervmmklqx:06123] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48e6ca5a6f]
[runnervmmklqx:06123] [ 8] plumed_master(+0x146dd)[0x55e2d46306dd]
[runnervmmklqx:06123] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48e682a1ca]
[runnervmmklqx:06123] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48e682a28b]
[runnervmmklqx:06123] [11] plumed_master(+0x15365)[0x55e2d4631365]
[runnervmmklqx:06123] *** End of error message ***
</pre>
{% endraw %}
