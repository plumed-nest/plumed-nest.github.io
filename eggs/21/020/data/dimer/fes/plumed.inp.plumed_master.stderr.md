**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:10295] *** Process received signal ***
[pkrvmq0rgcvqdmg:10295] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:10295] Signal code:  (-6)
[pkrvmq0rgcvqdmg:10295] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2daee45330]
[pkrvmq0rgcvqdmg:10295] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2daee9eb2c]
[pkrvmq0rgcvqdmg:10295] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2daee4527e]
[pkrvmq0rgcvqdmg:10295] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2daee288ff]
[pkrvmq0rgcvqdmg:10295] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2daf2a5ff5]
[pkrvmq0rgcvqdmg:10295] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2daf2bb0da]
[pkrvmq0rgcvqdmg:10295] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2daf2a5a55]
[pkrvmq0rgcvqdmg:10295] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2daf2a5a6f]
[pkrvmq0rgcvqdmg:10295] [ 8] plumed_master(+0x146dd)[0x55b9df7236dd]
[pkrvmq0rgcvqdmg:10295] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2daee2a1ca]
[pkrvmq0rgcvqdmg:10295] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2daee2a28b]
[pkrvmq0rgcvqdmg:10295] [11] plumed_master(+0x15365)[0x55b9df724365]
[pkrvmq0rgcvqdmg:10295] *** End of error message ***
</pre>
{% endraw %}
