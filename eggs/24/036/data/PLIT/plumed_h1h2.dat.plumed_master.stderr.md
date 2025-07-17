**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:06535] *** Process received signal ***
[pkrvmq0rgcvqdmg:06535] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06535] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06535] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc581a45330]
[pkrvmq0rgcvqdmg:06535] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc581a9eb2c]
[pkrvmq0rgcvqdmg:06535] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc581a4527e]
[pkrvmq0rgcvqdmg:06535] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc581a288ff]
[pkrvmq0rgcvqdmg:06535] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc581ea5ff5]
[pkrvmq0rgcvqdmg:06535] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc581ebb0da]
[pkrvmq0rgcvqdmg:06535] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc581ea5a55]
[pkrvmq0rgcvqdmg:06535] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc581ea5a6f]
[pkrvmq0rgcvqdmg:06535] [ 8] plumed_master(+0x146dd)[0x558029b336dd]
[pkrvmq0rgcvqdmg:06535] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc581a2a1ca]
[pkrvmq0rgcvqdmg:06535] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc581a2a28b]
[pkrvmq0rgcvqdmg:06535] [11] plumed_master(+0x15365)[0x558029b34365]
[pkrvmq0rgcvqdmg:06535] *** End of error message ***
</pre>
{% endraw %}
