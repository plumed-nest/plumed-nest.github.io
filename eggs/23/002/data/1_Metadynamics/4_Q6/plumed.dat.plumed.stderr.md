**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[runnervmeorf1:06698] *** Process received signal ***
[runnervmeorf1:06698] Signal: Aborted (6)
[runnervmeorf1:06698] Signal code:  (-6)
[runnervmeorf1:06698] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f65fac45330]
[runnervmeorf1:06698] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f65fac9eb2c]
[runnervmeorf1:06698] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f65fac4527e]
[runnervmeorf1:06698] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f65fac288ff]
[runnervmeorf1:06698] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65fb0a5ff5]
[runnervmeorf1:06698] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65fb0bb0da]
[runnervmeorf1:06698] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65fb0a5a55]
[runnervmeorf1:06698] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65fb0a5a6f]
[runnervmeorf1:06698] [ 8] plumed(+0x146dd)[0x55ed628516dd]
[runnervmeorf1:06698] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f65fac2a1ca]
[runnervmeorf1:06698] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f65fac2a28b]
[runnervmeorf1:06698] [11] plumed(+0x15365)[0x55ed62852365]
[runnervmeorf1:06698] *** End of error message ***
</pre>
{% endraw %}
