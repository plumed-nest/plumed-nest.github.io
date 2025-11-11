**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmw9dnm:09340] *** Process received signal ***
[runnervmw9dnm:09340] Signal: Aborted (6)
[runnervmw9dnm:09340] Signal code:  (-6)
[runnervmw9dnm:09340] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66f4245330]
[runnervmw9dnm:09340] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66f429eb2c]
[runnervmw9dnm:09340] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66f424527e]
[runnervmw9dnm:09340] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66f42288ff]
[runnervmw9dnm:09340] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66f46a5ff5]
[runnervmw9dnm:09340] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66f46bb0da]
[runnervmw9dnm:09340] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66f46a5a55]
[runnervmw9dnm:09340] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66f46a5a6f]
[runnervmw9dnm:09340] [ 8] plumed_master(+0x146dd)[0x5571e36446dd]
[runnervmw9dnm:09340] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66f422a1ca]
[runnervmw9dnm:09340] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66f422a28b]
[runnervmw9dnm:09340] [11] plumed_master(+0x15365)[0x5571e3645365]
[runnervmw9dnm:09340] *** End of error message ***
</pre>
{% endraw %}
