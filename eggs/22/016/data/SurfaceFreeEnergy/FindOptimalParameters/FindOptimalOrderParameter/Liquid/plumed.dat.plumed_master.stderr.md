**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmw9dnm:09458] *** Process received signal ***
[runnervmw9dnm:09458] Signal: Aborted (6)
[runnervmw9dnm:09458] Signal code:  (-6)
[runnervmw9dnm:09458] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d72845330]
[runnervmw9dnm:09458] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d7289eb2c]
[runnervmw9dnm:09458] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d7284527e]
[runnervmw9dnm:09458] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d728288ff]
[runnervmw9dnm:09458] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d72ca5ff5]
[runnervmw9dnm:09458] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d72cbb0da]
[runnervmw9dnm:09458] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d72ca5a55]
[runnervmw9dnm:09458] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d72ca5a6f]
[runnervmw9dnm:09458] [ 8] plumed_master(+0x146dd)[0x55c820d0b6dd]
[runnervmw9dnm:09458] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d7282a1ca]
[runnervmw9dnm:09458] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d7282a28b]
[runnervmw9dnm:09458] [11] plumed_master(+0x15365)[0x55c820d0c365]
[runnervmw9dnm:09458] *** End of error message ***
</pre>
{% endraw %}
