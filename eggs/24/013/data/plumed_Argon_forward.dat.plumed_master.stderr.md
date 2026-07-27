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
[runnervmvrwv9:05102] *** Process received signal ***
[runnervmvrwv9:05102] Signal: Aborted (6)
[runnervmvrwv9:05102] Signal code:  (-6)
[runnervmvrwv9:05102] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a42245330]
[runnervmvrwv9:05102] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a4229eb2c]
[runnervmvrwv9:05102] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a4224527e]
[runnervmvrwv9:05102] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a422288ff]
[runnervmvrwv9:05102] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a426a5ff5]
[runnervmvrwv9:05102] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a426bb0da]
[runnervmvrwv9:05102] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a426a5a55]
[runnervmvrwv9:05102] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a426a5a6f]
[runnervmvrwv9:05102] [ 8] plumed_master(+0x146dd)[0x556d84d106dd]
[runnervmvrwv9:05102] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a4222a1ca]
[runnervmvrwv9:05102] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a4222a28b]
[runnervmvrwv9:05102] [11] plumed_master(+0x15365)[0x556d84d11365]
[runnervmvrwv9:05102] *** End of error message ***
</pre>
{% endraw %}
