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
[runnervmw9dnm:06008] *** Process received signal ***
[runnervmw9dnm:06008] Signal: Aborted (6)
[runnervmw9dnm:06008] Signal code:  (-6)
[runnervmw9dnm:06008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1288045330]
[runnervmw9dnm:06008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f128809eb2c]
[runnervmw9dnm:06008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f128804527e]
[runnervmw9dnm:06008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12880288ff]
[runnervmw9dnm:06008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12884a5ff5]
[runnervmw9dnm:06008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12884bb0da]
[runnervmw9dnm:06008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12884a5a55]
[runnervmw9dnm:06008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12884a5a6f]
[runnervmw9dnm:06008] [ 8] plumed_master(+0x146dd)[0x55b0d03146dd]
[runnervmw9dnm:06008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f128802a1ca]
[runnervmw9dnm:06008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f128802a28b]
[runnervmw9dnm:06008] [11] plumed_master(+0x15365)[0x55b0d0315365]
[runnervmw9dnm:06008] *** End of error message ***
</pre>
{% endraw %}
