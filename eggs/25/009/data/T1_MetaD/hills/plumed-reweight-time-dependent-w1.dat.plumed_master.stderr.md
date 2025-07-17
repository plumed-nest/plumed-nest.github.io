**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w1.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:05551] *** Process received signal ***
[pkrvmq0rgcvqdmg:05551] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:05551] Signal code:  (-6)
[pkrvmq0rgcvqdmg:05551] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7effd3e45330]
[pkrvmq0rgcvqdmg:05551] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7effd3e9eb2c]
[pkrvmq0rgcvqdmg:05551] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7effd3e4527e]
[pkrvmq0rgcvqdmg:05551] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7effd3e288ff]
[pkrvmq0rgcvqdmg:05551] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7effd42a5ff5]
[pkrvmq0rgcvqdmg:05551] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7effd42bb0da]
[pkrvmq0rgcvqdmg:05551] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7effd42a5a55]
[pkrvmq0rgcvqdmg:05551] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7effd42a5a6f]
[pkrvmq0rgcvqdmg:05551] [ 8] plumed_master(+0x146dd)[0x558e85c8f6dd]
[pkrvmq0rgcvqdmg:05551] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7effd3e2a1ca]
[pkrvmq0rgcvqdmg:05551] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7effd3e2a28b]
[pkrvmq0rgcvqdmg:05551] [11] plumed_master(+0x15365)[0x558e85c90365]
[pkrvmq0rgcvqdmg:05551] *** End of error message ***
</pre>
{% endraw %}
