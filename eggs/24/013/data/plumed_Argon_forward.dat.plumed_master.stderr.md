**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmmklqx:07035] *** Process received signal ***
[runnervmmklqx:07035] Signal: Aborted (6)
[runnervmmklqx:07035] Signal code:  (-6)
[runnervmmklqx:07035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbba6c45330]
[runnervmmklqx:07035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbba6c9eb2c]
[runnervmmklqx:07035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbba6c4527e]
[runnervmmklqx:07035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbba6c288ff]
[runnervmmklqx:07035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbba70a5ff5]
[runnervmmklqx:07035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbba70bb0da]
[runnervmmklqx:07035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbba70a5a55]
[runnervmmklqx:07035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbba70a5a6f]
[runnervmmklqx:07035] [ 8] plumed_master(+0x146dd)[0x555dbbefa6dd]
[runnervmmklqx:07035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbba6c2a1ca]
[runnervmmklqx:07035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbba6c2a28b]
[runnervmmklqx:07035] [11] plumed_master(+0x15365)[0x555dbbefb365]
[runnervmmklqx:07035] *** End of error message ***
</pre>
{% endraw %}
