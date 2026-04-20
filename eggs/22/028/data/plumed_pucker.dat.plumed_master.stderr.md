**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmeorf1:06877] *** Process received signal ***
[runnervmeorf1:06877] Signal: Aborted (6)
[runnervmeorf1:06877] Signal code:  (-6)
[runnervmeorf1:06877] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb6fd645330]
[runnervmeorf1:06877] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb6fd69eb2c]
[runnervmeorf1:06877] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb6fd64527e]
[runnervmeorf1:06877] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb6fd6288ff]
[runnervmeorf1:06877] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6fdaa5ff5]
[runnervmeorf1:06877] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6fdabb0da]
[runnervmeorf1:06877] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6fdaa5a55]
[runnervmeorf1:06877] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6fdaa5a6f]
[runnervmeorf1:06877] [ 8] plumed_master(+0x146dd)[0x55f13ec7b6dd]
[runnervmeorf1:06877] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb6fd62a1ca]
[runnervmeorf1:06877] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb6fd62a28b]
[runnervmeorf1:06877] [11] plumed_master(+0x15365)[0x55f13ec7c365]
[runnervmeorf1:06877] *** End of error message ***
</pre>
{% endraw %}
