**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmmklqx:07945] *** Process received signal ***
[runnervmmklqx:07945] Signal: Aborted (6)
[runnervmmklqx:07945] Signal code:  (-6)
[runnervmmklqx:07945] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f36b8e45330]
[runnervmmklqx:07945] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f36b8e9eb2c]
[runnervmmklqx:07945] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f36b8e4527e]
[runnervmmklqx:07945] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36b8e288ff]
[runnervmmklqx:07945] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36b92a5ff5]
[runnervmmklqx:07945] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36b92bb0da]
[runnervmmklqx:07945] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36b92a5a55]
[runnervmmklqx:07945] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36b92a5a6f]
[runnervmmklqx:07945] [ 8] plumed_master(+0x146dd)[0x55771c0026dd]
[runnervmmklqx:07945] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f36b8e2a1ca]
[runnervmmklqx:07945] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f36b8e2a28b]
[runnervmmklqx:07945] [11] plumed_master(+0x15365)[0x55771c003365]
[runnervmmklqx:07945] *** End of error message ***
</pre>
{% endraw %}
