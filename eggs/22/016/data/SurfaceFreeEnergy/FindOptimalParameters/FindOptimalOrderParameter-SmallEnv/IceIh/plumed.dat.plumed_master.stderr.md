**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:08191] *** Process received signal ***
[pkrvmq0rgcvqdmg:08191] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08191] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08191] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95de645330]
[pkrvmq0rgcvqdmg:08191] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95de69eb2c]
[pkrvmq0rgcvqdmg:08191] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95de64527e]
[pkrvmq0rgcvqdmg:08191] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95de6288ff]
[pkrvmq0rgcvqdmg:08191] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95deaa5ff5]
[pkrvmq0rgcvqdmg:08191] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95deabb0da]
[pkrvmq0rgcvqdmg:08191] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95deaa5a55]
[pkrvmq0rgcvqdmg:08191] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95deaa5a6f]
[pkrvmq0rgcvqdmg:08191] [ 8] plumed_master(+0x146dd)[0x555da7bd76dd]
[pkrvmq0rgcvqdmg:08191] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95de62a1ca]
[pkrvmq0rgcvqdmg:08191] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95de62a28b]
[pkrvmq0rgcvqdmg:08191] [11] plumed_master(+0x15365)[0x555da7bd8365]
[pkrvmq0rgcvqdmg:08191] *** End of error message ***
</pre>
{% endraw %}
