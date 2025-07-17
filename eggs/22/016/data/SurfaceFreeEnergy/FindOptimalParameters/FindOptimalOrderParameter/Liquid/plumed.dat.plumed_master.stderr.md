**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:08112] *** Process received signal ***
[pkrvmq0rgcvqdmg:08112] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08112] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08112] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0dacc45330]
[pkrvmq0rgcvqdmg:08112] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0dacc9eb2c]
[pkrvmq0rgcvqdmg:08112] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0dacc4527e]
[pkrvmq0rgcvqdmg:08112] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0dacc288ff]
[pkrvmq0rgcvqdmg:08112] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0dad0a5ff5]
[pkrvmq0rgcvqdmg:08112] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0dad0bb0da]
[pkrvmq0rgcvqdmg:08112] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0dad0a5a55]
[pkrvmq0rgcvqdmg:08112] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0dad0a5a6f]
[pkrvmq0rgcvqdmg:08112] [ 8] plumed_master(+0x146dd)[0x55e0ccc5f6dd]
[pkrvmq0rgcvqdmg:08112] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0dacc2a1ca]
[pkrvmq0rgcvqdmg:08112] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0dacc2a28b]
[pkrvmq0rgcvqdmg:08112] [11] plumed_master(+0x15365)[0x55e0ccc60365]
[pkrvmq0rgcvqdmg:08112] *** End of error message ***
</pre>
{% endraw %}
