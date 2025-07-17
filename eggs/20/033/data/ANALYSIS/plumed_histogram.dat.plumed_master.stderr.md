**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:11698] *** Process received signal ***
[pkrvmq0rgcvqdmg:11698] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11698] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11698] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f31c6e45330]
[pkrvmq0rgcvqdmg:11698] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f31c6e9eb2c]
[pkrvmq0rgcvqdmg:11698] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f31c6e4527e]
[pkrvmq0rgcvqdmg:11698] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31c6e288ff]
[pkrvmq0rgcvqdmg:11698] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f31c72a5ff5]
[pkrvmq0rgcvqdmg:11698] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f31c72bb0da]
[pkrvmq0rgcvqdmg:11698] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f31c72a5a55]
[pkrvmq0rgcvqdmg:11698] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f31c72a5a6f]
[pkrvmq0rgcvqdmg:11698] [ 8] plumed_master(+0x146dd)[0x563c9d98a6dd]
[pkrvmq0rgcvqdmg:11698] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f31c6e2a1ca]
[pkrvmq0rgcvqdmg:11698] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f31c6e2a28b]
[pkrvmq0rgcvqdmg:11698] [11] plumed_master(+0x15365)[0x563c9d98b365]
[pkrvmq0rgcvqdmg:11698] *** End of error message ***
</pre>
{% endraw %}
