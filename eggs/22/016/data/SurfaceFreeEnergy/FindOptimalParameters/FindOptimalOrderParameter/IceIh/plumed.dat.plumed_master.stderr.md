**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmmklqx:07869] *** Process received signal ***
[runnervmmklqx:07869] Signal: Aborted (6)
[runnervmmklqx:07869] Signal code:  (-6)
[runnervmmklqx:07869] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8342645330]
[runnervmmklqx:07869] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f834269eb2c]
[runnervmmklqx:07869] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f834264527e]
[runnervmmklqx:07869] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83426288ff]
[runnervmmklqx:07869] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8342aa5ff5]
[runnervmmklqx:07869] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8342abb0da]
[runnervmmklqx:07869] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8342aa5a55]
[runnervmmklqx:07869] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8342aa5a6f]
[runnervmmklqx:07869] [ 8] plumed_master(+0x146dd)[0x55965d6546dd]
[runnervmmklqx:07869] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f834262a1ca]
[runnervmmklqx:07869] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f834262a28b]
[runnervmmklqx:07869] [11] plumed_master(+0x15365)[0x55965d655365]
[runnervmmklqx:07869] *** End of error message ***
</pre>
{% endraw %}
