**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmeorf1:05264] *** Process received signal ***
[runnervmeorf1:05264] Signal: Aborted (6)
[runnervmeorf1:05264] Signal code:  (-6)
[runnervmeorf1:05264] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f51ffa45330]
[runnervmeorf1:05264] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f51ffa9eb2c]
[runnervmeorf1:05264] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f51ffa4527e]
[runnervmeorf1:05264] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f51ffa288ff]
[runnervmeorf1:05264] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f51ffea5ff5]
[runnervmeorf1:05264] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f51ffebb0da]
[runnervmeorf1:05264] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f51ffea5a55]
[runnervmeorf1:05264] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f51ffea5a6f]
[runnervmeorf1:05264] [ 8] plumed_master(+0x146dd)[0x55e0387ad6dd]
[runnervmeorf1:05264] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f51ffa2a1ca]
[runnervmeorf1:05264] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f51ffa2a28b]
[runnervmeorf1:05264] [11] plumed_master(+0x15365)[0x55e0387ae365]
[runnervmeorf1:05264] *** End of error message ***
</pre>
{% endraw %}
