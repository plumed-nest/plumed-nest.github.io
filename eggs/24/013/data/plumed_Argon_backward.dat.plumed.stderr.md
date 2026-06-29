**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmmklqx:06968] *** Process received signal ***
[runnervmmklqx:06968] Signal: Aborted (6)
[runnervmmklqx:06968] Signal code:  (-6)
[runnervmmklqx:06968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff328a45330]
[runnervmmklqx:06968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff328a9eb2c]
[runnervmmklqx:06968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff328a4527e]
[runnervmmklqx:06968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff328a288ff]
[runnervmmklqx:06968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff328ea5ff5]
[runnervmmklqx:06968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff328ebb0da]
[runnervmmklqx:06968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff328ea5a55]
[runnervmmklqx:06968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff328ea5a6f]
[runnervmmklqx:06968] [ 8] plumed(+0x146dd)[0x55ed65f816dd]
[runnervmmklqx:06968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff328a2a1ca]
[runnervmmklqx:06968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff328a2a28b]
[runnervmmklqx:06968] [11] plumed(+0x15365)[0x55ed65f82365]
[runnervmmklqx:06968] *** End of error message ***
</pre>
{% endraw %}
