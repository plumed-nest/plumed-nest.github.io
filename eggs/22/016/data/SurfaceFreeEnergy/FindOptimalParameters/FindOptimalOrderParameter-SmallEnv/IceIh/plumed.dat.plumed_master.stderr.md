**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmmklqx:08021] *** Process received signal ***
[runnervmmklqx:08021] Signal: Aborted (6)
[runnervmmklqx:08021] Signal code:  (-6)
[runnervmmklqx:08021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc0b3c45330]
[runnervmmklqx:08021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc0b3c9eb2c]
[runnervmmklqx:08021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc0b3c4527e]
[runnervmmklqx:08021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0b3c288ff]
[runnervmmklqx:08021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0b40a5ff5]
[runnervmmklqx:08021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0b40bb0da]
[runnervmmklqx:08021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0b40a5a55]
[runnervmmklqx:08021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0b40a5a6f]
[runnervmmklqx:08021] [ 8] plumed_master(+0x146dd)[0x55edfe5086dd]
[runnervmmklqx:08021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc0b3c2a1ca]
[runnervmmklqx:08021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc0b3c2a28b]
[runnervmmklqx:08021] [11] plumed_master(+0x15365)[0x55edfe509365]
[runnervmmklqx:08021] *** End of error message ***
</pre>
{% endraw %}
