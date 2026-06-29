**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmmklqx:06984] *** Process received signal ***
[runnervmmklqx:06984] Signal: Aborted (6)
[runnervmmklqx:06984] Signal code:  (-6)
[runnervmmklqx:06984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8848e45330]
[runnervmmklqx:06984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8848e9eb2c]
[runnervmmklqx:06984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8848e4527e]
[runnervmmklqx:06984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8848e288ff]
[runnervmmklqx:06984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88492a5ff5]
[runnervmmklqx:06984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88492bb0da]
[runnervmmklqx:06984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88492a5a55]
[runnervmmklqx:06984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88492a5a6f]
[runnervmmklqx:06984] [ 8] plumed_master(+0x146dd)[0x5627de4c86dd]
[runnervmmklqx:06984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8848e2a1ca]
[runnervmmklqx:06984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8848e2a28b]
[runnervmmklqx:06984] [11] plumed_master(+0x15365)[0x5627de4c9365]
[runnervmmklqx:06984] *** End of error message ***
</pre>
{% endraw %}
