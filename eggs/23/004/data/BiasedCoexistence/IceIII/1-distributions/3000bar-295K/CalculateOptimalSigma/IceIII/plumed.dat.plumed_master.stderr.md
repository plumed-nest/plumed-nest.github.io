**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:07842] *** Process received signal ***
[pkrvmq0rgcvqdmg:07842] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07842] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07842] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5836045330]
[pkrvmq0rgcvqdmg:07842] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f583609eb2c]
[pkrvmq0rgcvqdmg:07842] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f583604527e]
[pkrvmq0rgcvqdmg:07842] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58360288ff]
[pkrvmq0rgcvqdmg:07842] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58364a5ff5]
[pkrvmq0rgcvqdmg:07842] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58364bb0da]
[pkrvmq0rgcvqdmg:07842] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58364a5a55]
[pkrvmq0rgcvqdmg:07842] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58364a5a6f]
[pkrvmq0rgcvqdmg:07842] [ 8] plumed_master(+0x146dd)[0x55a94d8f46dd]
[pkrvmq0rgcvqdmg:07842] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f583602a1ca]
[pkrvmq0rgcvqdmg:07842] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f583602a28b]
[pkrvmq0rgcvqdmg:07842] [11] plumed_master(+0x15365)[0x55a94d8f5365]
[pkrvmq0rgcvqdmg:07842] *** End of error message ***
</pre>
{% endraw %}
