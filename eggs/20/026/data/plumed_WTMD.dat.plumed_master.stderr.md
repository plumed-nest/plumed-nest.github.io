**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:11947] *** Process received signal ***
[pkrvmq0rgcvqdmg:11947] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11947] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f31b1c45330]
[pkrvmq0rgcvqdmg:11947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f31b1c9eb2c]
[pkrvmq0rgcvqdmg:11947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f31b1c4527e]
[pkrvmq0rgcvqdmg:11947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31b1c288ff]
[pkrvmq0rgcvqdmg:11947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f31b20a5ff5]
[pkrvmq0rgcvqdmg:11947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f31b20bb0da]
[pkrvmq0rgcvqdmg:11947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f31b20a5a55]
[pkrvmq0rgcvqdmg:11947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f31b20a5a6f]
[pkrvmq0rgcvqdmg:11947] [ 8] plumed_master(+0x146dd)[0x55a05112f6dd]
[pkrvmq0rgcvqdmg:11947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f31b1c2a1ca]
[pkrvmq0rgcvqdmg:11947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f31b1c2a28b]
[pkrvmq0rgcvqdmg:11947] [11] plumed_master(+0x15365)[0x55a051130365]
[pkrvmq0rgcvqdmg:11947] *** End of error message ***
</pre>
{% endraw %}
