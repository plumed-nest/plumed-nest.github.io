**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmmklqx:07830] *** Process received signal ***
[runnervmmklqx:07830] Signal: Aborted (6)
[runnervmmklqx:07830] Signal code:  (-6)
[runnervmmklqx:07830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3812245330]
[runnervmmklqx:07830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f381229eb2c]
[runnervmmklqx:07830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f381224527e]
[runnervmmklqx:07830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38122288ff]
[runnervmmklqx:07830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38126a5ff5]
[runnervmmklqx:07830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38126bb0da]
[runnervmmklqx:07830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38126a5a55]
[runnervmmklqx:07830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38126a5a6f]
[runnervmmklqx:07830] [ 8] plumed_master(+0x146dd)[0x555816ba26dd]
[runnervmmklqx:07830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f381222a1ca]
[runnervmmklqx:07830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f381222a28b]
[runnervmmklqx:07830] [11] plumed_master(+0x15365)[0x555816ba3365]
[runnervmmklqx:07830] *** End of error message ***
</pre>
{% endraw %}
