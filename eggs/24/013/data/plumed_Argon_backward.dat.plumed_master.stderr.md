**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmi13qx:33969] *** Process received signal ***
[runnervmi13qx:33969] Signal: Aborted (6)
[runnervmi13qx:33969] Signal code:  (-6)
[runnervmi13qx:33969] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48d4645330]
[runnervmi13qx:33969] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48d469eb2c]
[runnervmi13qx:33969] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48d464527e]
[runnervmi13qx:33969] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48d46288ff]
[runnervmi13qx:33969] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48d4aa5ff5]
[runnervmi13qx:33969] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48d4abb0da]
[runnervmi13qx:33969] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48d4aa5a55]
[runnervmi13qx:33969] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48d4aa5a6f]
[runnervmi13qx:33969] [ 8] plumed_master(+0x146dd)[0x55c55c1b16dd]
[runnervmi13qx:33969] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48d462a1ca]
[runnervmi13qx:33969] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48d462a28b]
[runnervmi13qx:33969] [11] plumed_master(+0x15365)[0x55c55c1b2365]
[runnervmi13qx:33969] *** End of error message ***
</pre>
{% endraw %}
